## MERN EXERCISE TRACKER

### Setting up remote origin 
https://help.github.com/en/github/using-git/changing-a-remotes-url#switching-remote-urls-from-https-to-ssh

### Setting up SSH
https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account

### In backend directory
`npm i express cors mongoos dotenv`
+ cors@2.8.5
    => `Cross Origin Resource Sharing`, this allows AJAX request to skip same origin policy and access resources from remote host
    => The `cors` package provides the express middleware that can enable different options
+ mongoose@5.9.1
    => Interacts with MongoDB throught NodeJS server
+ express@4.17.1
    => light weight and fast web framework for `NodeJS` 
+ dotenv@8.2.0
    => Which loads ENV variables fom `dotenv` file into process.env. This Makes development simpler, so instead of setting variable in our development machine they can be stored in file. 
