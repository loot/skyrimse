Contributing To The Masterlist
==============================

## Filing Issues

If you're about to file an issue for some suggested change, please consider instead making the change yourself and submitting it as a pull request. Pull requests are much more likely to be quickly acted on, so they're the best way to get your change into the masterlist.

## Making Changes

LOOT's masterlists are [versioned](https://loot.github.io/docs/contributing/Masterlist-Versioning). Before making any changes, please make sure that you're working on the correct branch for LOOT's latest release.

If you are new to contributing to projects on GitHub, the [How To Contribute](https://loot.github.io/docs/contributing/How-To-Contribute) wiki page is a good starting point.

The format and syntax of the masterlist is [fully documented](https://loot-api.readthedocs.io/en/stable/metadata/introduction.html), and other information on how to edit the masterlist can be found on the [Masterlist Editing](https://loot.github.io/docs/contributing/Masterlist-Editing) wiki page.

When submitting changes, please keep them as focused as possible. If you'd like to make several unrelated changes across multiple mods, open separate pull requests for each mod you edit. This makes reviewing your changes much easier, keeps the commit history organized and easier to navigate, and makes reverting changes easier when necessary. Note that if a mod contains multiple plugins, you can make changes to any of those plugins in the same pull request. If you want to make a change to a separate mod that is related to the mod you're editing (e.g., you're editing Mod A's metadata & Mod B should load after it), you can include that in the same pull request as well. You can also edit several unrelated mods if your changes are contained to a single topic, e.g., updating Bash Tags or cleaning data. If, for example, you're updating the Bash Tags of several mods and would like to add cleaning data for them as well, you should do that in a separate pull request.

If you send a pull request, then discover that you have made a mistake, feel free to make additional commits to fix it. You don't need to squash your commits or open a new pull request to keep your commit history tidy; whoever merges your pull request can squash it for you. You can also mark your pull request as a draft if it isn't ready to be merged.

### Testing Changes

Pull requests and all commits to the masterlist repository are automatically run through a validator to check for syntax errors.

Nevertheless, it is advisable to test your changes on your own LOOT install before sending a pull request, as they may have valid syntax but not have the intended effect. Instructions on how to do so can be found on [LOOT's wiki](https://loot.github.io/docs/contributing/Quickly-Testing-Your-Masterlist-Changes).
