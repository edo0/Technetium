# Maintainer wanted
Looking for someone willing to take over maintainership of the project.

# What is Technetium?
A focused approach to taming the new Firefox 89+'s Proton design, restituting some elements retired alongside the old Photon UI

It gets its name from Technetium-99m, agent used for [Single Photon Emission Computed Tomography](https://en.wikipedia.org/wiki/Single-photon_emission_computed_tomography)


### What has been changed?
- Icons have been reintroduced, in a smaller menu
- Compact mode has been re-enabled
- Close-tab icon is always displayed, regardless of the number of open tabs 
- Speaker icon always visible on tabs reproducing A/V content
- I wish to thank the [Lepton](https://github.com/black7375/Firefox-UI-Fix)'s developer, whose work served as a base for my less radical restyling


### How to apply Technetium to your Firefox?
-  Enter `about:config` in your URL bar; search for the parameter `toolkit.legacyUserProfileCustomizations.stylesheets` and make sure it is set to `true` 
-  Now enter `about:support` in your URL bar
-  Find the `Profile Directory` entry and click the `Open Directory` button
-  Copy in that folder the `user.js` file and the `chrome` folder from the Technetium release package
-  In `about:support`, click `Clear startup cache...`

## Screenshots

![screenshot-Technetium](https://user-images.githubusercontent.com/16632292/122136471-dca69480-ce42-11eb-8a49-6a13ad77c9aa.png)

### Really missing tab separators?
They can sure be restored, by adding [this code](https://pastebin.com/yHggpULx) before the last `}` in `userChrome.css`

### In the News   
As featured on OMG!Ubuntu!

https://www.omgubuntu.co.uk/2021/06/dont-like-firefoxs-new-look-try-one-of-these-tweaks

### Donations
If you like my work, please consider donating to the Free Software Foundation!   
Free software is what allows all this to happen, and they have been championing it (GPL license, GNU, GNOME, GIMP...) for 36 years already!

https://my.fsf.org/donate  

![image](https://user-images.githubusercontent.com/16632292/122197289-53ba4800-ce98-11eb-9d8c-f318f587619f.png)

### Bugs and Feedback
Please don't hesitate to fill in a bug report if something seems not to be working as expected, or you have any piece of advice
