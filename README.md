# RepoFetcher

This web application allows users to fetch and display GitHub repositories for a given username. It leverages the GitHub API to retrieve user details, repositories, and their languages.

## Features

1. **User Details Display**: Displays user details such as avatar, username, and bio.
2. **Total Repositories Count**: Shows the total number of repositories a user has on their GitHub profile.
3. **Repository Cards**: Dynamically generates cards for each repository with details like name, description, and a link to the repository.
4. **Pagination**: Implements pagination to navigate through the user's repositories.

## Assumption
1.  i have assumed the user can fetch a maximum of 100 repositpries with maximum of 10 repos per page i.e. 10 pages . i can make the project 
    fetch more repos but it will give http error 403

2.  i have not made separate files for html css and js . but i can do that if you ask for it
