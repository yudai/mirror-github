# Mirror gihub

## What is this

This command line tool allows you to mirror repositories on github into your srever. You can choose the repositories by user/organization name.

## Usage
### Generate OAuth2 token (optional)

If you need to mirror private repositories, you have to generate an OAuth2 token to access them.

Run 

    ./gen-mirror-github-token


This command will generate your token and save it on ~/.mirror_github_token (default).

### Execute mirroring

    ./mirror-github -d /path/to/mirror/directory user1 user2 ...


This command will clone all the repositories that are owned by user1 and user2.

