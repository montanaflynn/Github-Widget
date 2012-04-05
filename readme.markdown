Want to share your repo's and activity on your blog or portfolio? This simple widget allows you to embed an iframe widget that pulls from a specific account and repo on Github.  

### Get Started
All you have to do is download this repo and include an iframe pointing to the github-widget.html file Make sure to change the user and repo in the src attribute.

```
<iframe src="/path/to/github-widget.html?user=montanaflynn&repo=Github-Widget" allowtransparency="true" frameborder="0" scrolling="0" width="292" height="290"></iframe>          
```

##### From command line:
```
$ cd /where/you/want/your/repo/
$ git clone git@github.com:montanaflynn/Github-Widget.git
$ nano Github-Widget/example.html
```

##### Not a Command Line Ninja? Try this:
First <a href="https://github.com/montanaflynn/Github-Widget/zipball/master">download the widget files</a> and extract them.  Now open example.html and change the iframe url to include your username and repo. You can then copy this iframe and include it on your website wherever you choose.  Make sure the path matches up.

### Coming Soon
WordPress Plugin,
Multiple Repo Support, 
Unobtrusive Javascript (no iframe)

### Authors and Contributors
This widget is a fork from @ruanmer's <a href="https://github.com/ruanmer/Github-Widget">original Github-Widget</a>.  Apparently it is also based off @markdotto's <a href="https://github.com/markdotto/github-buttons">GitHub-Buttons</a>.  Additionally it relies on the GitHub API, so thanks to everyone involved on that.