#Unit 7 Project 1: Mr. Potato Head

![Imgur](http://i.imgur.com/Vy06FW3.gif)

Together we can create a Mr. Potato Head using GitHub! 


##Remember: **Fork, Change, Push, Pull**
In Cloud 9 terminal:

```
 git status
```

You should see that potatohead.html and potato.css are modified, like this:

```
	modified:   potatohead.html
  modified:   potato.css
```

### Make a commit
Stage your changes in the index with `git add .`, then commit them.  The string after `-m` in `git commit` is the commit message. Don't use "Commit message" as your message!
Use "FIRST_NAME added BODY_PART to Mister Potato Head" (eg Simon added arms to Mister Potato Head)

```
 git add .
 git commit -m "Commit message"  <<< but change the message!
```


### Send this commit up to github
Push your local commit up to github

```
 git push origin master
```

look at your github: You should see the commit you just made!  If you click "Commits" you can see the all of the work that has been put into Mr Potato Head, and you are at the top!

### Make a pull request

From your GitHub create a "New Pull Request" (the green button) to send your changes to the instructor.  The instructor will merge all of the changes (everyone's body parts), and at the end hopefully we'll have a whole Mr. Potato Head.
