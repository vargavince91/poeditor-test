# poeditor-test
This repo tests poeditor

By editing the README file, I trigger a push event. I set up a webhook that exports strings from POEditor into this repository on push events. Expectation: I add this commit, and immediately after that commit, POEditor makes a new commit on my behalf, updating one string in the English JSON file.

I'm editing the README again. It's a push event. I expect to see updated strings. Hm...
