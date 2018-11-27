Start hugo server (optional)

```bash
hugo server -D
```
If you decided to start the server, you can go to the site using the following URL:

http://localhost:1313

The development environment is at c/hugo/sites/personal-site

To create a new post execute:

```bash
hugo new posts/first-activity-with-carpentries.md
```

Then you can edit and work on your post.

After you finish you can update your git local repository

``` bash
git add
git commit
```

Then you can update github repository

```bash
git push origin master
```

Now you can deploy your static site to /c/Users/ferga/fergarciafer.github.io

From c/hugo/sites/personal-site

Execute:

```bash
hugo
```

Then copy the contents of the public directory to /c/Users/ferga/fergarciafer.github.io

From public directory execute

cp -r * /c/Users/ferga/fergarciafer.github.io

Next, go to /c/Users/ferga/fergarciafer.github.io, update the repository and push it to github:

``` bash
git add *
git commit
git push origin master
```
