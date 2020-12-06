Well-structured Unity project template.

Begin by cloning the repository and removing all git references:

```
$ git clone https://github.com/nizsanli/unity_template.git YourProjectName
$ cd YourProjectName
$ rm -rf .git
```

Add your project to Unity, select your desired editor version, and allow it to reimport. Adjust the README for your project and begin tracking:

```
$ git init
$ git add Assets ProjectSettings Packages .gitignore README.md
$ git commit -m "initial setup"
```

