# Service Layer Contracts

This document defines the contracts for the application's service layer, which encapsulates the core business logic.

## Album Service

**Functions:**

-   `createAlbum(name: string): Promise<Album>`: Creates a new album.
-   `getAlbums(): Promise<Album[]>`: Retrieves all albums.
-   `updateAlbumPosition(albumId: string, newPosition: number): Promise<void>`: Updates the position of an album.
-   `deleteAlbum(albumId: string): Promise<void>`: Deletes an album and all its photos.

## Photo Service

**Functions:**

-   `addPhotoToAlbum(albumId: string, photoPath: string): Promise<Photo>`: Adds a photo to an album.
-   `getPhotosInAlbum(albumId: string): Promise<Photo[]>`: Retrieves all photos in an album.
-   `removePhoto(photoId: string): Promise<void>`: Removes a photo from an album.
