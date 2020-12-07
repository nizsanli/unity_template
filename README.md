Well-structured Unity project template.

Begin by starting a new Unity project and emptying out the Assets directory. Clone the repository into the Assets directory and remove all git references:

```
$ git clone https://github.com/nizsanli/unity_template.git .
$ rm -rf .git
```

From the project root, remove the README, move the .gitignore up one level, and begin tracking the project:

```
$ rm Assets/README.md
$ mv Assets/.gitignore ./
$ git init
$ git add Assets ProjectSettings Packages .gitignore
$ git commit -m "initial setup"
```
