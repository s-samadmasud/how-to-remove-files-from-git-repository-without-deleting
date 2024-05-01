# how-to-remove-files-from-git-repository-without-deleting

This repository provides a simple guide on how to remove files from a Git repository without deleting them from your local file system.

## Introduction

Removing files from a Git repository can be necessary when you want to untrack certain files or clean up your repository. This guide will walk you through the process step by step.

## Steps

### Step 1: Move to the Desired Folder

Navigate to the folder containing the repository using your terminal or command prompt.

### Step 2: Remove the File from the Repo

Execute the following command to remove the file from the repository but not from the local file system:

```
$ git rm --cached filename
```

Replace `filename` with the actual name of the file you wish to remove.

### Step 3: Commit the Changes

Commit your changes with an appropriate message using:

```
$ git commit -m "your message"
```

### Step 4: Push the Changes

Finally, push your changes to the remote repository with:

```
$ git push
```

## Conclusion

By following these steps, you can successfully remove files from your Git repository without affecting the local copies. This is particularly useful for files that were committed by mistake or contain sensitive information that should not be shared publicly.
