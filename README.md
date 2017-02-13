# example-1

Let's suppose that I'm trying to create a program with the letters of the alpahebet, each letter is a "feature" of the program, and is contained in its own file.

So the goal is to create a program with four files (the first four features) each containing a letter:

<table>
  <tr>
  <td><b>Filename</b></td><td><b>Contents</b></td>
  </tr>
  <tr>
    <td>A.txt</td><td>A</td>
  </tr>
   <tr>
    <td>B.txt</td><td>B</td>
  </tr>
    <tr>
    <td>C.txt</td><td>C</td>
  </tr>
    <tr>
    <td>D.txt</td><td>D</td>
  </tr>
</table>

The state of all files in the repository at a certain time is called a commit.  Commits can be organized into categories called branches.

For this example I'll use a **master** branch for capturing major achievement points, such as releases, a **devel** branch for capturing finished features while they are completed prior to a release, and as many **feat** branches as necessary for capturing, or saving, the state of each feature as it is being completed.

So let's imagine I'd like to work on a major stage of the project (a release) that adds the first four features (A, B, C, and D).  So first, I will create a new feature branch for it, and I'll name it **feat-A** so that it's always clear what this branch is for.

By creating the new branch, I will have cloned all the current code to the new branch, and the old code is still intact just the way I left it before I begin work on this new feature.

For feature A all I need to do is create a text file *A.txt* with contents *A*.  To do this, from [github.com/violanotes/example-1](github.com/violanotes/example-1) navigate to the feat-A branch page display by finding the **branch** drop-down menu, select the **feat-A** branch, and then click **New File**.  Give the file a name, fill in the contents appropriately, then freeze (commit) it in time by giving it a description, such as *Completed Feature A*, and clicking the commit button at the bottom of the page.

Now the feature A has been completed, but there is not yet a capture of it in the **devel** branch.  Let's do that now.

You can use the drop down menu, or access the feature A branch at [https://github.com/violanotes/example-1/tree/feat-A](https://github.com/violanotes/example-1/tree/feat-A).  Once at the **feat-A** branch, click **New pull request** beside the drop down menu.  We want the pull request to *request* the **devel** branch to *pull* current files from the **feat-A** branch.  On the new page that appears, in the **base:** drop-down menu, select the **devel** branch so that the request will pull from the **devel** branch.  Then we'll name this capture something briefly descriptive like *Completed Feature A* (and we could add a thorough description in addition).  Then click **Create pull request**.  Because its a request, we'll be able to review the request to accept it or reject it, and we can click **Merge pull request** on the page that appears, and then click **Confirm merge** to complete the operation.

Can you try the following:

* create a branch for **feat-B** and **feat-C**
* create *B.txt* and *C.txt* in their respective branches and commit each file with a description for each commit
* create new pull requests for each branch to their base **devel** branch, **feat-B** and **feat-C**
* *Do Not* merge the pull requests.  This will let me see if we can see pull requests that the other person creates.


