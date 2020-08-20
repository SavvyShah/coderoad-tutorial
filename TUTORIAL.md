# How to create a CodeRoad tutorial

CodeRoad is a VSCode extension that allows you to play interactive coding tutorials in your editor. There are only few things you need to learn to create interactive tutorials with CodeRoad. Follow these instructions carefully to create your first CodeRoad tutorial.

## 1. Setup a repository

> Make a Git repository to keep your tutorial files. 

CodeRoad tutorials are stored and loaded using Git, a popular version control system. If you're unfamiliar with Git, think of it as a way to save or load progress from checkpoints called "commits". 

### 1.1 

Make remote and local repository for your tutorial files

- Go to GitHub and create a new repository for yourself named `first-tutorial`. Find "Add .gitignore'' dropdown option and type "Node" and select it to add a node `.gitignore`. Fill in remaining fields and click create.
- After you click create, it takes you to the repo. Copy the URL for the repo, it should look like: `https://github.com/your-username/first-tutorial.git`.
- Open a terminal locally and find a place to clone your repo. Enter `git clone https://github.com/your-username/first-tutorial.git` with the repo URL you copied in place of that URL to clone it.

### 1.2

Add a `.gitignore` if you haven't already by copying the below into a file named `.gitignore`

```
node_modules
package-lock.json
```

## 2. Create TUTORIAL.md

## 3. Create project files

## 4. Making tests

## 5. Create coderoad.yaml

## 6. Building tutorial.json

## 7. Run your tutorial

## 8. Editing your tutorial

## 9. Restart the tutorial with new lessons