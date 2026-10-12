# Build ZenScoreboard against the real Paper API

The previously supplied JAR was compiled against compatibility stubs and is not safe to use. Do not install it.

## Build on GitHub from a phone
1. Create a new GitHub repository and upload the contents of this folder (the files inside `ZenScoreboard`, not the parent folder).
2. Open the repository's **Actions** tab.
3. Select **Build ZenScoreboard**, then **Run workflow** if it has not run automatically.
4. Wait for the workflow to finish successfully.
5. Open the successful run and download the `ZenScoreboard-1.0.0` artifact. Extract the downloaded artifact ZIP to get `ZenScoreboard-1.0.0.jar`.
6. Upload that JAR to `plugins/` on BaoHost, remove the old broken ZenScoreboard JAR first, then fully restart the server.

If Maven reports that the Paper API version cannot be resolved, check the Paper Maven repository/version availability and update the dependency in `pom.xml`; do not use fake API stubs.
