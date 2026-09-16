# PACKAGE-NAME

## Npm Publish Checklist

1. [ ] Set NPM_TOKEN
    1. Go to settings
    2. Select Actions under Secrets and Variables
    3. New repository secret
    4. Set name as "NPM_TOKEN" and set the Secret that you get from npm
2. [ ] Clone the repo to directly inside unity project
    - This will create .meta files
3. [ ] Create and checkout "Prepare-Npm" branch
4. [ ] Run "npm init" after checkout in the root directory of the repo
5. [ ] Edit packages.json with relative information about the package
    - Update "name"
    - Update "displayName"
    - Update "description"
    - Update "keywords" if necessary
    - Update "license"
    - ! Do not update the version !
7. [ ] Update docfx_project/api/index.md file
8. [ ] Create "Runtime" folder in the root of the repo
9. [ ] Create/Move the files inside the "Runtime" folder
10. [ ] Commit and push the changes
