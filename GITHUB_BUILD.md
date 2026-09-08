# Build automatically with GitHub Actions

1. Create a new GitHub repository.
2. Upload/extract all files from this project into the repository root.
3. Commit the files to the `main` branch.
4. Open **Actions**.
5. Select **Build Minicraft Battle SMP**.
6. Click **Run workflow**.
7. When it finishes with a green check, open the workflow run.
8. Under **Artifacts**, download `MinicraftBattleSMP-1.21.11`.
9. Inside the artifact is the built JAR. Put the normal (non-sources) JAR into your Fabric 1.21.11 `mods` folder.

The workflow follows GitHub's documented Gradle build/artifact pattern and uses Java 21 for this Minecraft project.
