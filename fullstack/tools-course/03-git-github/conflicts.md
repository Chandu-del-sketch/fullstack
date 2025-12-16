# How did i handlle the merge conflicts

- Git stops the merge when the same lines are changed in different branches.

- Check conflicted files

- Use `git status` to see which files have conflicts.

- Open the conflicted file

**Decide the correct code**
    Current branch code
    Incoming branch code
    Or a combination of both

**Remove conflict markers**
    `Delete <<<<<<<, =======, >>>>>>>` after fixing.

**Test the code**
    - Ensure the application runs correctly after resolving conflicts.

- Stage the resolved files

- `git add <file>`

**Complete the merge**

- `git commit`

- By this way i will handle merge conflicts