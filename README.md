# blogo

Using gohugo.io to host fernando.st

## Deploying new posts

Create new post with

    hugo new content/posts/name-of-post.md

Write the post on this new file.

Check locally that the blog looks like expected with the new post

    hugo server -D

If happy edit the `draft` tag in the files header to `false` and the add, commit and push the new file.

This will trigger a new deployment.
