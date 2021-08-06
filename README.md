# Stud files [Docker, Tests]
This Project create a base for other projects as long as they are based on node.js and they have client and server.

The folder structure is based on a project that is complex enought to have users, authentification and react on the client.

It contains:
  - A basic express server, with the set up for mongo db and with the setup of postgresql, so you just have to delete one (or maybe i will put them in different branches)
  - All the stud files and node configuration of a client that is react based

## Installation
  1. clone Repository in your folder of preference with `git clone <this url>` or the branch with `git clone -b <branchname> --single-branch <this url>`
  2. `git remote add project <the url of your project>`
  3. Change the remote:
    1. `git push --set-upstream project main`
    2. `git add .` 
    3. `git commit -m 'First commit`
    4.  `git push`
  4. `git remote rm origin`
