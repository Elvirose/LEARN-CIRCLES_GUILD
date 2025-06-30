# Github Actions

- Created a github action that responds to when we push something into the repo.
- For Github Action I created a holder .github/workflows/ in my repo

>**Github Action Code**


name: Echo Text 
on:
  push:          
    branches:
      - main     
jobs:
  say-hello:
    runs-on: ubuntu-latest 
    
    steps:
      - name: Say Hello
        run: echo "Hello from GitHub Actions!" 



*Screenshot from actions tab in this repo*