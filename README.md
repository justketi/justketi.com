# How it works

When you open [https://justketi.com](https://justketi.com) it shows you `index.html`. It's default page, you can modify it but don't delete it!

When you open other page, it will open corresponding path as in your repository on github, for example:

[https://justketi.com/src/about.html](https://justketi.com/src/about.html) -> it will show you page in `src/about.html`.

# How to push changes

Enter your directory, if you're not there:

```
cd projects/justketi.com
```

Be sure that you pulled your latest changes. Before you start your work, just run in terminal:

```
git pull
```

After you made your change that you want to push to your site, just run following commands

```
git status
git add --all
git commit -m "update"
git push origin main
```

If for some reason, you cannot push your changes, probably you need to pull your changes:

```
cd projects/justketi.com
git pull origin master --no-rebase
```

If this does not help, just contact your guru. 
