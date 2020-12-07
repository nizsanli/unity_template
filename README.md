Well-structured Unity project template.

Begin by creating a new Unity project and emptying the Assets directory. From the empty Assets directory, clone the repository and remove all git references:

```
$ git clone https://github.com/nizsanli/unity_template.git .
$ rm -rf .git
```

Remove the README and move the .gitignore up one level:

```
$ rm README.md
$ mv .gitignore ./
```

Begin tracking the project from the root:

```
$ git init
$ git add Assets Packages ProjectSettings .gitignore
$ git commit -m "initial setup"
```
