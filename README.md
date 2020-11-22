# git-crypt - Test

## About

This repository contains a test for using [git-crypt](https://www.agwa.name/projects/git-crypt/) at Leka.

The idea is to be able to store encrypted important files in a public repository.

Important files include:

- API keys
- certificates
- configs
- etc.

## How to use

1. Install git-crypt on your Mac

    ```
    $ brew install git-crypt
    ```
    
1. Clone the repository

    ```
    $ git clone https://github.com/leka/test_git_crypt
    ```
    
1. Ask @ladislas to be added to the repository
1. Unlock the repository 

    ```
    $ git-crypt unlock
    ```
     
You can then see, use and edit the encrypted files. When you commit, files are automatically encrypted.

If needed, you can use `git-crypt lock` to re encrypt the files.
