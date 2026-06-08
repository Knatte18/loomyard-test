# Tasks

# Layer A

## **#000:** Define core domain types [A]
[core-types](proposal-core-types.md)

The Task and Store types and their JSON contract.

# Layer B

## **#001:** Persistent storage layer [B]
[storage-layer](proposal-storage-layer.md)
Depends on: #000

Load and save tasks.json with full validation.

## **#002:** CLI subcommands [B]
[cli-commands]
Depends on: #000

upsert, get, list, set-phase, merge, rerender.

# Layer C

## **#003:** HTTP API server [C]
[http-api](proposal-http-api.md)
Depends on: #001, #002

Expose the wiki over a small HTTP API.

## **#004:** API authentication [C]
[auth] [active]
Depends on: #001

Token-based auth for the HTTP API.

# Layer Z

## **#006:** Spike: GraphQL endpoint [Z]
[experiment-graphql](proposal-experiment-graphql.md)

Throwaway experiment, off the critical path.

# Someday

## **#005:** Write end-user documentation
[write-docs]

User guide and API reference.

# Done

## **#007:** Initial feasibility spike
[initial-spike] [done]

Proved the end-to-end approach works.
