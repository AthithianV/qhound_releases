# Check List for New Version Release

1. Chande the Versions in tarui.config.json, package.json, Cargo.toml
2. Commit and push all code to Remote.
3. Create a tag: `git tag -a v1.0.0 -m "Release version 1.0.0"`
4. Push the Tag: `git push origin v1.0.0`. This will trigger the github actions.
5. Now take the windows bundle(build locally) and Apple bundle(github actions) and upload it to `qhound-release`.
6. Release the new bundles.
7. Update the lastest.json with the new pub key and bundle URL.
8. Update the URL in Landing Page.
