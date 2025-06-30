# Github Actions

- Created a github action that responds to when we push something into the repo.
- For Github Action I created a holder .github/workflows/ in my repo

>**Github Action Code**
```

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

```

*Screenshot from action tab in this repo*
![image](https://github.com/user-attachments/assets/c36cc108-56f8-4403-a075-a06d8dc814b0)
