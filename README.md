# DocuSimple meta-manager

The meta-manager creates and manipulates file metadata. This includes tags, file names, authors, source, dates, times, types, reminders, and permissions. It is a local component, meaning it is intended to run on the same machine where the files are stored.

Meta-manager exposes a JSON API over HTTP, allowing a web UI or mobile app to interact with the file metadata. On the backend, it uses a local flat file database for storing the information.
