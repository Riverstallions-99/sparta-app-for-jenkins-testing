# Use this repo with Jenkins

## About the app
- "app" folder stores Sparta app
- uses Node JS v20
- webhook included: pushes to git repo trigger Jenkins
- develop branch triggers Jenkins
- Jenkins merges develop with main
- updates to app code deploys to EC2 instance
