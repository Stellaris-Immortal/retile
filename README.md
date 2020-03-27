# Stellaris Immortal
 
Stellaris Immortal is a total rebuild mod of Stellaris, focusing on speed, balance and sane gameplay. It's also open source, so feel free to contribute!
 
## How to contribute
 
Have an idea? Great! Head over to our [discord](https://discord.gg/Jty9qk8) to discuss it with the devs. You can also check out the issues page on [Github](https://github.com/gebnar/retile/issues) and see if we've already talked about this!

### Submitting pull requests
If you aren't a member of the mod team, and want to contribute, that's awesome (and easy!). Just fork the repository (there should be a little button on the top right saying "fork"), clone it to your machine, make all the changes you want, commit and push back to GitHub.

Then, go back to our repository, click the "submit pull request" buttton (on the right, under the number of commits). Click "compare across forks", choose "staging" as your base (that is, where you want your changes to end up), and choose your fork as the head repository. Select the branch on your fork with your changes, and create the PR!

## Submitting bug reports
 
Check out the issues page on [Github](https://github.com/gebnar/retile/issues) and see if we've already talked about this! If not, please submit a report! The more info you give, the faster we can solve it. Its especially helpful if you tell us what kind of mods you use - SI is incompatible with most content mods, so your problem might start there.
 
 ## Installation

You can get SI from our [workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=1891758612).
 
You can also install by downloading this repository:

 - Follow the system-specific instructions [Windows](#windows) [Linux](#linux)
 - The mod should appear in your launcher. You may also need to unsubscribe from the workshop version of the mod for this to work properly. If stellaris shows you a harddrive icon on the left of the mod instead of the Steam icon, you're golden.

### Windows
 - Choose the branch you want. We recommend you use the Staging branch, for the latest "stable" content.
 - Clone the branch into your local mod folder `C:/Users/{YOUR_USER}/Documents/Paradox Interactive/Stellaris/mod`, or download a zip and extract it there.
 - Rename the downloaded folder to "retile" if it is named anything else (such as "retile-staging")
 - Move the "retile.mod" file from the "retile" folder out into the mod folder.
 - When you're finished, you should see the following paths:
   - /mod/retile/readme.md
   - /mod/retile.mod

### Linux

```bash
cd ".local/share/Paradox Interactive/Stellaris/mod"
git clone https://github.com/Stellaris-Immortal/retile.git
ln retile/retile.mod .
```