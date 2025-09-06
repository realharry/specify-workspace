# Data Model for Photo Organization Application

This document describes the data model for the application, based on the entities identified in the feature specification.

## 1. Photo

Represents a single image file.

**Attributes:**
-   `id`: (Primary Key) A unique identifier for the photo.
-   `file_path`: The absolute path to the image file on the local filesystem.
-   `album_id`: (Foreign Key) The ID of the album this photo belongs to.
-   `created_at`: The timestamp when the photo was added to the application.

## 2. Album

Represents a collection of photos.

**Attributes:**
-   `id`: (Primary Key) A unique identifier for the album.
-   `name`: The name of the album (e.g., "2025-09-06").
-   `created_at`: The timestamp when the album was created.

## Relationships

-   An `Album` can have many `Photo`s.
-   A `Photo` belongs to one `Album`.
