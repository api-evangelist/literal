# Literal Club

Literal is a modern social reading and book tracking platform with a GraphQL API that allows developers to manage and access reading lists, shelves, reviews, highlights, reading goals, book recommendations, and social reading clubs.

## API

- **Type:** GraphQL
- **Endpoint:** `https://literal.club/graphql/`
- **Method:** POST with JSON body containing `query` and optional `variables`
- **Authentication:** JWT bearer token via `Authorization: Bearer <token>` header

## Developer Resources

- [API Documentation](https://literal.club/developers)
- [Developer Community Club](https://literal.club/clubs/dev)
- [Support](mailto:support@literal.club)

## Key Capabilities

- Book lookups by slug, ID, ISBN, or search
- Reading state management (want to read, currently reading, finished)
- Custom shelves and reading lists
- Reviews and ratings
- Highlights and notes (moments)
- Reading goals and progress tracking
- Social features: follow users, join clubs
- Author and edition information

## Authentication

Obtain a JWT token using the `login` mutation with email and password credentials. Tokens are valid for 6 months. Pass the token as an `Authorization: Bearer <token>` header on subsequent requests.

## Links

- Homepage: https://literal.club
- API Docs: https://literal.club/developers
- Support: support@literal.club
