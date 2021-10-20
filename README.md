# machine_learning_jupyter_ensmbles
machine learning concepts derivations and python coding
## Ways to push local repo to this feed
1. start building a local repo <br>``git init``
2. generate new ssh key pair if you haven't<br>``ssh-keygen -t rsa -C http://github.com/ChauserMondieu``
3. copy your public key to Github
4. test connection with ssh <br> ``ssh -T git@github.com``
5. first submit your code into stage<br> ``git add *``
6. then commit your code into local repo</br> ``git commit -m "first commit"``
7. next build up remote repo which is linked to github repo<br> ``git remote add origin https://github.com/ChauserMondieu/machine_learning_jupyter_ensmbles.git``
8. finally push your local repos into remote repo<br> ``git push -u origin master``

## Questions on connecting with ont-time-token via HTTPS instead of SSH
1. navigate to Settings -> Developer Settings ->Personal Access Tokens
2. generate new PATs with expiry date
3. save this token

## Other knowledge about gitbash 
