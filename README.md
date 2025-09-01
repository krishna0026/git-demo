Example scenario: when we push from two different-2 local repos to 1 git repo.

You have one repo on Laptop A and another repo on Laptop B.

Both are linked to the same GitHub repo.

If you commit on Laptop A and push → GitHub updates.

If you then commit on Laptop B, you must first git pull (to sync A’s changes) before pushing B’s new changes.
so our local repo at same level with git repo then only we can push .
