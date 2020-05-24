# CSS Art Competition

### Welcome, all!
You're in the principal repository for an experiment I ([@vicnicius](https://github.com/vicnicius)) decided to try out. An open contest for any one part of the Github community to join. The goal of the competition is to produce great art in the form of web pages using HTML and CSS. The definition of great art will also be determined openly in this same repository.

## How it works
Among other things, this repository contains one special HTML file, [next.html](https://github.com/bitsofart/cssac/blob/master/next.html) and one CSS file [next.css](https://github.com/bitsofart/cssac/blob/master/next.css). Those two artifacts are the ones the contesters will be dealing with the whole time. 
At the beginning of every competition, contesters will have a version of this specia HTML file filled with content. The contest's principal goal is to produce the CSS file that, with the given HTML, makes a *beautiful piece of art* when rendered.

### Selecting the content for the next running contest
The competition starts with the selection of what will be the content for the contest. The choice of new content works as follows:
- Anyone can send a suggestion in the form of a new issue using the Content Suggestion template. Those will be labeled "Next piece."
- The content of the issue represents the exact content used for the next contest if it is a winner. (Notice that some HTML tags are also allowed as content there).
- The community will then vote on the content suggestions by reacting to an issue with an emoji.
- At the end of the currently running week, @janethebot will go through all suggestions, select the one with more positive emoji reactions and close all the others. The following emojis are considered positive: 👍😀🎉❤️🚀.
- [@janethebot](https://github.com/janethebot) will also commit the content of the selected suggestion to a new version of the `next.html` file*. This file is the one that contenders will work on top of in the next running contest.
_* Together with the winner suggested content, this file will also contain some extra information and placeholders for other things like a link to the winner user Github page, a link to the user who suggested the content and links with additional information about the contest._

### Submitting an entry
Contesters will work on top of the selected content for the week they want to compete, which should always be the current `next.html` file. To participate in the contest for a given week, the participant must:
- Submit a pull request. This PR can only contain changes to one file: the `next.css` file. Pull requests containing changes in other files other than `next.css`.
- [@janethebot](https://github.com/janethebot) will deploy all valid entries, and Github will provide a link to it in the Pull Request actions area, where the community will be able to look at the rendered work and evaluate it. Then:
- The community will react to every entry with an emoji.
- At the end of the week, [@janethebot](https://github.com/janethebot) will go through valid entries (PRs) for that week and count the positive reactions. The following emojis are considered positive: 👍😀🎉❤️🚀.
- The entry with the most positive reactions for that week will be considered the winner. [@janethebot](https://github.com/janethebot) will take care of merging and deploying the winner version to the contest's home page.
- The winning version will stay on the home page while the next week's contest is running.
Competitions will take place regularly weekly. Every Monday at 0:00:00 UTC+0, a new contest starts.
_** Re-opened PRs or re-opened issues with content suggestions won't be considered valid._
_*** All the code automation will also be available in the form of open-source code in other repositories._