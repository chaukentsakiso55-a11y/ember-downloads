# Installing offline models

1. Fetch the resource catalogue over HTTPS.
2. Show the resource name, languages, size, licence and available storage.
3. Require an explicit Download action.
4. Download to a temporary file and verify SHA-256.
5. Atomically move verified files into app-private storage.
6. Mark the engine Ready only after the model loads successfully.

Never bundle placeholder or unlicensed model archives.
