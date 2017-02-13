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

Now I will 
