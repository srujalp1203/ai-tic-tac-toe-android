# Database Design

The application uses a local SQLite database to persist game results.

## Stored Attributes

- Timestamp
- Winner (X / O / Draw)
- Difficulty level

## Purpose

- Maintain historical records
- Enable statistics visualization
- Persist data across sessions

The database is accessed via a dedicated helper class to ensure separation of concerns.
