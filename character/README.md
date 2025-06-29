# Character Query by ID

This task includes GraphQL queries and results to retrieve specific characters by their ID using the `character(id: ID!)` field.

## Files

- `character-id-1.graphql` → Query for character with ID 1
- `character-id-1-output.json` → Output of the above query

- `character-id-2.graphql` → Query for character with ID 2
- `character-id-2-output.json` → Output of the above query

- `character-id-3.graphql` → Query for character with ID 3
- `character-id-3-output.json` → Output of the above query

- `character-id-4.graphql` → Query for character with ID 4
- `character-id-4-output.json` → Output of the above query

## Fields Fetched

Each query retrieves the following fields:

- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`
---

## Characters List by Page

This section contains GraphQL queries and responses that retrieve a paginated list of all characters using the `characters(page: Int)` field.

### Pages Covered
- Page 1 → `characters-page-1.graphql`, `characters-page-1-output.json`
- Page 2 → `characters-page-2.graphql`, `characters-page-2-output.json`
- Page 3 → `characters-page-3.graphql`, `characters-page-3-output.json`
- Page 4 → `characters-page-4.graphql`, `characters-page-4-output.json`

### Fields Fetched
- `id`
- `name`
- `status`
- `image`

### API Source
[https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)
