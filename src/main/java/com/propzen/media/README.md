# media

Property photos: presigned S3 upload links, resizing into thumb/medium/large, ordering and cover photo. Photo bytes never pass through the app.

**Owns tables:** property_photos

**Inside `internal/`:** web, domain, persistence, jobs (photo processing, stuck-upload cleanup), storage (S3 access)

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
