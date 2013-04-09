# Using GitHub Pages for Hackathon Web Hosting

This guide is intended to provide F2 Hackathon participants instructions for using a quick and easy hosting solution. By committing code to GitHub Pages (`gh-pages`), you'll have public access to your assets at:

[`http://openf2.github.io/Hackathon/`](http://openf2.github.io/Hackathon/)

## Disclaimer

Using GitHub Pages makes any static resources (HTML, CSS, JS) available to the **public**. If you don't want your code in the public domain, **do not use this option**.

Also:

* GitHub Pages does not provide SSL support
* This is only an option for static resources (there is no PHP, Java or C# available on `gh-pages`).

## Setup

If you don't have Git installed, install it. [GitHub provides a step-by-step tutorial](https://help.github.com/articles/set-up-git).

If you don't want to use the command line, there are Windows and Mac clients available.

* [GitHub for Mac](http://mac.github.com/)
* [GitHub for Windows](http://windows.github.com/)

## Clone the Hackathon Repo

Once you have Git and GitHub installed, you need the **Hackathon** repo. Clone it to your computer.

Command line:

`git clone git@github.com:OpenF2/Hackathon.git`

Or get help: [Working with Repositories](https://help.github.com/articles/working-with-repositories)

## Checkout `gh-pages`

All of your code must be in the `gh-pages` branch in the Hackathon repository. Since anyone can commit to this repo, simply switch from `master` to `gh-pages`.

`git checkout gh-pages && git pull`

## Add Your code

Create a folder for your code within the `gh-pages` branch. It is **best practice** to use your name or something unique to identify your assets.

For example:

`..\OpenF2\Hackathon\a_unique_name\`

Then commit your code:

`git commit -a -m 'Adding my code'`

Finally push it to GitHub:

`git push origin gh-pages`

## Wait 

Once changes are committed to `gh-pages`, you'll need to wait a couple of minutes for them to appear. Then rejoice!

[`http://openf2.github.io/Hackathon/a_unique_name/`](http://openf2.github.io/Hackathon/a_unique_name/)

## Help

If you need help working with GitHub Pages, review [pages.github.com](http://pages.github.com/) or find someone in the [F2 Working Group](mailto:BLD-F2WorkingGroup@markit.com).