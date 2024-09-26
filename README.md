
# sramp

energy efficient


[comment]: # (The following section was added for your reference, it should be deleted.)
___

In order to interact with this project, make sure you have provided your ssh key [here](/settings/#nav-ssh-tab).

By convention, the original / primary remote repository is called *origin*.

## Instructions

### Local Project Setup - Git Commands

If you are starting a brand new project without a local repository, here are the suggested Git commands:

```console
git clone ssh://git@repositories.efabless.com/christisherin2004/sramp.git
cd sramp
... do some changes
git push -u origin main
```


If you already have a local Git repository, initialized with _git init_, you will need to associate your local repository with the Efabless Repository remote location. The following Git commands will add Efabless Repository as a remote repository and push your changes to the main branch.

```console
git remote add origin ssh://git@repositories.efabless.com/christisherin2004/sramp.git
git pull origin main --rebase --allow-unrelated-histories
git push -u origin main
```


If you already have a remote repository, for example one on GitHub, use the Git command below to add another remote Git repo (make sure that each repo has its unique ID, e.g. _origin_, _ef-repo_ in the example below).

```console
git remote add ef-repo ssh://git@repositories.efabless.com/christisherin2004/sramp.git
git push -u ef-repo main --force
```

### How To Update Your Project Cover Image

A default cover.png has already been added to the root directory of this remote repository.  

If your project is not private, this image can be viewed in the [project search results list](https://platform.efabless.com/projects/public).

To show your own cover image, replace cover.png with a file called 'cover' and an allowed image extension ('.jpg', '.jpeg', '.png', '.gif', '.webp') and then push your changes.  

(Maximum allowed file size: 1 MB)

___

