# ClassMeet

## install packages

```console
foo@bar:~$ npm install
```

## Run developement server

```console
foo@bar:~$ npm run dev
```

## To contribute

```console
foo@bar:~$ git clone https://github.com/yashvardhan-verma/classmeet.git

foo@bar:~$ cd classmeet

foo@bar:~$ git remote add upstream https://github.com/yashvardhan-verma/classmeet.git
```

## Synchorize your work

```console
foo@bar:~$ git checkout main
foo@bar:~$ git fetch upstream
foo@bar:~$ git merge upstream/main
foo@bar:~$ git push origin main
```

## Create a new branch for a feature or bugfix

```console
foo@bar:~$ git checkout -b <feature-branch>
```

This will create a new branch out of master branch. Now start working on the problem and commit your changes.

```console
foo@bar:~$ git add .
foo@bar:~$ git commit -m <commit message>
```

## Push your code

```console
foo@bar:~$ git push origin <feature-branch>
```

Now go to github and compare and make a pull request.