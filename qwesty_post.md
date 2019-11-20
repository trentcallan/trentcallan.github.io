[Home](https://trentcallan.github.io/) | [Resume](resume.md)

# Qwesty iOS application

Here is a link to the app on the app store: <https://apps.apple.com/us/app/qwesty/id1486407706?ls=1>

I decided to make an iOS application to put on the app store to learn about the process a bit more.  

Qwesty is an iOS application designed to help organize your goals and to dos in the form of quests (if you have ever played video games or RPG’s then this might look familiar).  Ironically I wanted to create an app to help make myself more productive.  You create your own quests, define how long it’s going to take and define how many times it should repeat itself.  Qwesty helps motivate you by having a character progression system.  You unlock animations, backgrounds and floors as customization options for your characters scene.

One trouble I had was with scheduling the quest if it repeats.  First I was going to try to use local notifications and check which ones were delivered to see add the new quest.  But I decided it would be satisfactory to just check the dates of what I called “Going to be available quests.’  When a new quest is created it is put in available and going to be available quests.  Then whenever the Quest View Controller is loaded it checks to see if a ‘Going to be available quest’ is ready to be an ‘Available Quest.’  This way may not be a good way to scale an app because it checks the whole array of ‘Going to be Available Quests,’ but I was having trouble finding another solution.  This way was satisfactory for my app because I don’t think most people will have more than roughly 10 repeatable quests

I learned a lot about the app store submission process.  Also how to use in-app purchases since my app contains one.  The process was all relatively easy to create a product in your App Store Connect Account.  I looked up and followed a tutorial on how to set up the code for an in app store purchase and it worked well.  I ran into a problem when I submitted my app for review.  I was unaware that the app needed a restore purchases button that would be able to restore a users purchase if they delete the app and then download it again.  After that it was a easy fix and re-submission.
