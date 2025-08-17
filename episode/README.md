# Episode Query

This query fetches details of a specific episode by its ID from the Rick and Morty GraphQL API.

## Query

File: `episode-page-1.graphql`

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
