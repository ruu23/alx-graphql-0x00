# GraphQL Character Queries

This task retrieves character information using the `character(id: ID!)` field from the GraphQL API.

For each character ID (1, 2, 3, 4), a GraphQL query was written requesting the following fields:

- id
- name
- status
- species
- type
- gender

Each query file (`character-id-X.graphql`) contains the GraphQL query.
Each output file (`character-id-X-output.json`) contains the actual JSON response returned by the API.
