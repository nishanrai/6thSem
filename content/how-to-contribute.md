---
title: "How to Contribute"
disableToc: true
---

### This is the barebones

{{<mermaid align="center">}}
graph TD;
    A(Decide to Contribute) -->|fork the repository| B[Make Desired Changes]
    B --> C{Is Change Good?}
    C -->|NO| D[Make it good]
    D --> C
    C -->|YES| E[Good! You're ready to share it with everybody]
    E -->|commit and push to your forked repository| F(Make a pull request)
{{< /mermaid >}}


{{%expand "I am a bit confused" %}}

The pages on this site are generated from the
[csitauthority/6thSem](https://github.com/csitauthority/6thSem) repository on GitHub.  The
format is [Markdown](https://learn.netlify.com/en/cont/markdown/) with some
additional "[shortcodes](https://learn.netlify.com/en/shortcodes/)", such as the
"Tip" at the end of this page.

#### If you have commit access

The "Edit this page" link (top right) opens GitHub's online text editor.  Changes
made this way will automatically update the site via a webhook - it's great
for fixing typos, small changes, etc.

#### If you don't have commit access

The "Edit this page" link leads to a page where you can "fork" the `docs`
repository and edit your copy. Please create a "pull request" to get your
changes incorporated into this site.

If you expect to make more changes, you can also add a [new
issue](https://github.com/csitauthority/6thSem/docs/issues) on GitHub with your plans and
a request for direct edit/commit access as contributor.

#### More substantial changes

For larger changes, it's much more convenient to use Hugo's _live preview_
server mode, which shows the effect of each change as soon as it is saved to
file.  The basic steps to do this are:

1. install [Hugo](https://gohugo.io) (it runs on just about [any
   platform](https://github.com/gohugoio/hugo/releases))
1. clone the [csitauthority/6thSem](https://github.com/csitauthority/6thSem) repository
1. a customized version of [Learn theme](https://github.com/matcornic/hugo-theme-learn)
   is already associated with the repository. To use it, the commands in order are `git submodule init` and `git submodule update`
1. launch Hugo in server mode: `hugo server`
1. open <http://localhost:1313> in your browser
1. _extend and modify the documentation ..._
1. every time you save, the browser will update

{{% notice tip %}}
A convenient setup is to keep your editor and browser open,
side-by-side.
{{% /notice %}}

---

# Perhaps you need a walkthrough?

> This walkthrough assumes that you have made a github account prior to doing this

1. Fork this entire repository
1. Make desired changes
	* Such as adding files to `content/`
	* Deleting content deemed unnecesary
	* Adding resources such as Questions/Notes/Links etc
1. Determine if the changes you've made is good
	* A good change is one which does not break the system
	* The first thing to ensure is that your repo is not _behind_ the master when pushing. Learn to be a commit ahead.
	* If that seems hard^, then atleast make sure there are no conficting changes
	* Ofcourse, we at CSITauthority __do not__ ignore bad commits but, bad commits will take longer to appear on the main website.
	* _Lastly_, don't sweat the details. If you feel its good, push it. Moderators won't let anything that shouldnt break, break.
1. Now, if the change your propose is good to go, please commit it one final time then push to your `master`
1. Then you need to make a pull request from your forked repository.
1. Once your pull request is submitted, moderators will make sure necessary changes are made. Your contributions are valuable to us.
1. Expect to see __YOUR__ content soon! You are now an official contributor. *Yes, our website automatically enlists you in the contributor list as long as you have configured your Git-bash properly*
1. Happy Contributing! and Welcome to the family.

---

# Still not good enough?
# [> Maybe you should read this first <](https://csitauthority.github.io/page/contribute/)

>Still Confused? [We're just a click away](https://m.me/csitauthority)

{{% /expand%}}