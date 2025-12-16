# How to create and document releases

- To create and document releases, first we have to finilize the entire code that all features and bugs are fixed, Merge required branches(main) and finally test the application. if all goes perfect then only we have to create and document the releases.

**Create the release**
- to create the release first we have to create a version tag, for ex: V1.0.0 by terminal

`git tag v1.0.0`
`git push origin main`

- Then open Github Repo and then click **Releases** then click **create a new release** and select version tag which we already pushed by terminal(v1.0.0). Then enter release details i.e **release title** and add **release notes** and then attach assests(this is optional) and then finally click **Publish release** to publish the release and github will creates a permanent release page.

- This is the way i have created and published the releases.