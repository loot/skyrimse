Contributing To The Masterlist
==============================

## Filing Issues

If you're about to file an issue for some suggested change, please consider instead making the change yourself and submitting it as a pull request. Pull requests are much more likely to be quickly acted on, so they're the best way to get your change into the masterlist.

## Making Changes

LOOT's masterlists are [versioned](https://loot.github.io/docs/contributing/Masterlist-Versioning). Before making any changes, please make sure that you're working on the correct branch for LOOT's latest release.

If you are new to contributing to projects on GitHub, the [How To Contribute](https://loot.github.io/docs/contributing/How-To-Contribute) wiki page is a good starting point.

The format and syntax of the masterlist is [fully documented](http://loot.github.io/docs/0.8.1/LOOT%20Metadata%20Syntax.html) (an offline copy is also available in the `docs` folder of each LOOT release), and other information on how to edit the masterlist can be found on the [Masterlist Editing](https://loot.github.io/docs/contributing/Masterlist-Editing) wiki page.

If you send a pull request, then discover that you have made a mistake and make additional commits to fix it, please squash those additional commits to keep the commit history tidy. If you squash your commits, you don't need to open a new pull request. If you don't know how to squash commits, whoever merges your pull request can do it for you.

### Testing Changes

Pull requests and all commits to the masterlist repository are automatically run through a validator to check for syntax errors.

Nevertheless, it is advisable to test your changes on your own LOOT install before sending a pull request, as they may have valid syntax but not have the intended effect. Instructions on how to do so can be found on [LOOT's wiki](https://loot.github.io/docs/contributing/Quickly-Testing-Your-Masterlist-Changes).
