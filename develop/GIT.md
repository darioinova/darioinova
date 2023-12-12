# GIT Notes
[HOME](../README.md)


## Basic usage

## Commit comments

Best practice: [Conventional Commits](www.conventionalcommits.org)

### Normal Commit
Notes from [QooMon](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)
<pre>
<b><a href="#types">&lt;type&gt;</a></b></font>(&lt;optional scope&gt;): &lt;description&gt;
<i>empty separator line</i>
&lt;optional body&gt;
<i>empty separator line</i>
&lt;optional footer&gt;
</pre>

### Merge Commit
<pre>
Merge branch '<b>&lt;branch name&gt;</b>'
</pre>
<sup>Follows default git merge message</sup>

### Revert Commit
<pre>
Revert "<b>&lt;reverted commit subject line&gt;</b>"
</pre>
<sup>Follows default git revert message</sup>


### Types
* API relevant changes
    * `feat` Commits, that adds or remove a new feature
    * `fix` Commits, that fixes a bug
* `refactor` Commits, that rewrite/restructure your code, however does not change any API behaviour
    * `perf` Commits are special `refactor` commits, that improve performance
* `style` Commits, that do not affect the meaning (white-space, formatting, missing semi-colons, etc)
* `test` Commits, that add missing tests or correcting existing tests
* `docs` Commits, that affect documentation only
* `build` Commits, that affect build components like build tool, ci pipeline, dependencies, project version, ...
* `ops` Commits, that affect operational components like infrastructure, deployment, backup, recovery, ...
* `chore` Miscellaneous commits e.g. modifying `.gitignore`
