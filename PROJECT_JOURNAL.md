# Project Journal

## Steps to Create This Project:

1. Initialize the new project with Rails specifying the version, setting it up for API mode, and configuring it to use PostgreSQL:
   `rails _7.1.3.2_ new . --api -d postgresql`

2. Generate a new model named `Message` with a string attribute called `greeting`:
   `rails g model Message greeting:string`

3. Create a new controller within the `api/v1` namespace called `Messages` and include an `index` action:
   `rails g controller api/v1/Messages index`
