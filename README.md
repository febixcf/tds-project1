- This project scrapes GitHub users located in Mumbai with over 50 followers using
  the url https://api.github.com/search/users?q=location:Mumbai+followers:>50&per_page={per_page}&page={page}",
  using python requests library and the Url can found in [Github API documentation](https://docs.github.com/en/rest), Where {per_page} and {page} are query strings.
  
- One surprising discovery was the variety of programming languages used across repositories, Many users showed a preference for popular languages like Python and JavaScript, indicating trending technologies in the region and there are some new languages which i have never heard of.

- From the GitHub repo data, it looks like a lot of users are not licensing their work. I really think it’s important for developers to put a license on their projects. Doing this clears up how others can use their code and makes it way easier for people to contribute. Plus, it gives their work more credibility in the open-source scene.

# GitHub Users in Mumbai

This repository contains two CSV files: `users.csv` and `repositories.csv`, detailing GitHub users from Mumbai with over 50 followers and their public repositories.

## Data Sources

1. **users.csv**: Contains information about users in Mumbai.
2. **repositories.csv**: Lists public repositories for each user.
