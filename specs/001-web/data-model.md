# Data Model: Web-Based Reading Notes App

## Entities

### Note
- **Attributes**:
  - `id` (string, unique identifier)
  - `title` (string, optional)
  - `content` (string, required)
  - `createdAt` (timestamp, auto-generated)
  - `updatedAt` (timestamp, auto-updated)

### User
- **Attributes**:
  - `id` (string, unique identifier)
  - `settings` (object, user preferences)

## Relationships
- **User-Note**: One-to-Many
  - A user can have multiple notes.