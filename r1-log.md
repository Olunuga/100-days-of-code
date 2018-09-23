# #100DaysOfCode Log - Round 1 - [Mayowa]

The log of my #100DaysOfCode challenge. Started on [September 5, Wednesday, 2018].

## Log
Continuing the ios weda app project i started in August 2018. Would be updating the progress here on wards for the challenge.

<h2 align="center">
R1-Day 1: September 5, Wednesday, 2018
</h2>   

**Today's Progress**: Handled UITable view when data is empty. Tried using tableview.backgroundview but ended up using a UIView as the background and setting its visibility as needed. 
Had issues after removing pod files from my git repository (error with RealmSwift), solved it by deleting the project derived files in xcode directory.

**learnt about** 
- Tableview backgroundview 
- Updating a FORKED project with upstream code.

**Thoughts:** Feels good to start commiting to coding again.


**Link to work:** [tweet](https://twitter.com/myorwah/status/1037281957737111555)

<h2 align="center">
R1-Day 2: September 6, Thursday, 2018
</h2>   

**Today's Progress**: Added logic to handle location service scenarios such as when it is enabled or disabled, or when location service is denied for the app. Got it to work at first but introduced some bugs, and was also having issues with UIlabel wrapping in auto layout  

**learnt about** 
- Openinging Appplication preferences : setting from within the app

**Thoughts:** Was frustrated today though cause of unexpected bugs.


**Link to work:** [tweet](https://twitter.com/myorwah/status/1037574801534148608)

<h2 align="center">
R1-Day 3: September 7, Friday, 2018
</h2>   

**Today's Progress**: Fixed the bug i introduced yesterday by separating the block of code and nesting the location enabled logic and location access granted logic. Don't know if this is the best way yet, but got it to work. Also handled network connectivity (this was too long and not striaght forward compared to android, would hopefuly get a better method as time goes on)

**learnt about** 
- Auto indenting code in xcode using control + I
- Supposedly how to check for network reachability (didnt go deeper)

**Thoughts:** Was almost lost wihin the code, Not that the code is not well formatted. Then checking for network reachabilty was to me cumbersom in IOS.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1037968901332717568)

<h2 align="center">
R1-Day 4: September 8, Saturday, 2018
</h2>   

**Today's Progress**: Worked on opening weather details using segue from another viewController, Added new views to the storyboard and fixed the bug occured when navigating back from weather details viewController. 


**learnt about** 
- Methods of passing data between viewControllers (using instance property, delegation pattern, instance function, NotificationCenter(broadcast in android :-)), closure ) https://learnappmaking.com/pass-data-between-view-controllers-swift-how-to/

**Thoughts:** Felt like i didn't do much today, but closed out a github issue today though. I am also supposed to learn aboout passing data accross viewControllers

**Link to work:** [tweet](https://twitter.com/myorwah/status/1038429084051759104) 

<h2 align="center">
R1-Day 5: September 9, Sunday, 2018
</h2>   

**Today's Progress**: Closed out an issue where the local repository cannot fetch data by location. Added migration to realm database. Saved users last known location using Userdefaults (kinda like sharedprefernces in android) and updated the realm query to filter by last used location.


**learnt about** 
- Revisted using UserDefaults and Realm query and Migration

**Thoughts:** Same as yesterday, Need to set higher goals.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1038429084051759104) 


<h2 align="center">
R1-Day 6: September 10, Monday, 2018
</h2>   

**Today's Progress**: Closed out anoher issue Yayi! Worked on making user set their preferred location and use this when next they open the app untill they choose to use GPS


**learnt about** 
- More on UserDefaults
- Also revisted Alert and Alert action.

**Thoughts:** No thoughts for today.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1039063649694957569) 


<h2 align="center">
R1-Day 7: September 12, Wednesday, 2018
</h2>   

**Today's Progress**: Closed out issue with deleting stale data which delete valid date data too when user is offline for days, instead deleting just the old ones. Which close out another issue. Next i would love to 
 [ ] refactor the code by moving the logic to the view model
 [ ] convert location to using lat and long


**learnt about** 
- Date compasrism
- Date components.

**Thoughts:** Couldn't test the app on my device because i back dated the phone which cause debug profile to fail and somehow couldnt do it on emulator too : this is kinda crazy though.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1039740897490075648) 


<h2 align="center">
R1-Day 8: September 13, Thursday, 2018
</h2>   

**Today's Progress**: Just battled with adding a new plugin to podFile in this case i added cocoapd-keys plugin to handle secrete keys in other not to commit them to VCS. 

**learnt about** 
- CocoaPod plugins
- Ways of saving api keys.
- How to solve some build issue by deleting xcode derivedData folder.

**Thoughts:**  I need to start planning ahead what to the next day so that i won't be stuck thinking about what to do while time is running out.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1040148287431630848) 

Implement this https://hackernoon.com/a-cleaner-way-to-organize-your-ios-debug-development-and-release-distributions-6b5eb6a48356 next instead of using cocoapad-keys -[ ] done


<h2 align="center">
R1-Day 9: September 14, Friday, 2018
</h2>   

**Today's Progress**: Did further work in setting up build configurations using Configuration setting files instead of cocoa-pod keys (good to have knowledge of both though). Did a set up for Release, development and debug configs. Should be setting up AppCenter for build automation on github.

**learnt about** 
- How to use Configuration setting files from [HackerNoon](https://hackernoon.com/a-cleaner-way-to-organize-your-ios-debug-development-and-release-distributions-6b5eb6a48356)
- Setting up Scheme for different build configurations

**Thoughts:**  Enjoyed today, :-) maybe because i leant something new or that i think is new.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1040508450965532672) 

<h2 align="center">
R1-Day 10: September 15, Sarturday, 2018
</h2>   

**Today's Progress**:  Spent much time (Think wasted ) watching some tutrials on youtube when all i had to was 
`let view = UIView()
view.backgroundColor = UIColor(white: 1, alpha : 0.5)`
Sha complteted changing the background of a selected cell and fixed deleting weather data by location

**learnt about** 
- UIView class
- UIColor
- Also some videos on youtube on how to add subviews with NIB.

**Thoughts:**  Felt i wasted much time today watching youtube video tutorials.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1040957521526177793) 

<h2 align="center">
R1-Day 11: September 17, Monday, 2018
</h2>   

**Today's Progress**: Skipped another day, was kind of stuck on what to do next. Ended up deciding to start cloning major apps (Crazy right). Created a new project with the tabbed navigation controller and added major icons.

**learnt about** 
- Tabbed Navigation Controller

**Thoughts:**  followed the saying "set your goals high."

**Link to work:** [tweet](https://twitter.com/myorwah/status/1041745099191988224) 

<h2 align="center">
R1-Day 12: September 18, Tuesday, 2018
</h2>   

**Today's Progress**: Continued on the Medium app clone. Created the simple story cells and populated the UItbaleView with it. Setting up the layout was a bit difficult, still needs some more depth on auto layout.

**learnt about** 
- More on UITableView
- How to set TableView separator color

**Thoughts:**  No thougts

**Link to work:** [tweet](https://twitter.com/myorwah/status/1041967866592014336) 


<h2 align="center">
R1-Day 13: September 19, Wednesday, 2018
</h2>   

**Today's Progress**: Created multiple row type SwipeableCell and WideCell in the UITableView to handle the compact cards. Added MaterialComponent Card for the collectinView Cell.

**learnt about** 
- Learnt about UICollectionView
- How to use UICollectionFlowLayoutDelegate to set item size and insets.
**Thoughts:**  Feels good learning another new thing.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1042321905758425093) 

<h2 align="center">
R1-Day 14: September 20, Thursday, 2018
</h2>   

**Today's Progress**: Added logic to show and hide title section in the swipe-able cell section by working with the view's constraint. Also added color to view background.

**learnt about** 
- Constraints and how to use them to modify views
- UIColor -  initing color using RGB values. 
**Thoughts:**  Almost did not want to stand up from the bed.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1042695470932533248) 

<h2 align="center">
R1-Day 15: September 21, Friday, 2018
</h2>   

**Today's Progress**: Added buttons to the UITableView cells and intercept it when clicked within the Host ViewController to display menu for each cell. Used delegation pattern. Created a protocol within the cell class and passed action to the host cell.

**learnt about** 
- More on protocol. Delegation pattern
- Revisted Enum creation.
**Thoughts:**  same as yesterday.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1043048346481582080) 

<h2 align="center">
R1-Day 16: September 22, Sarturday, 2018
</h2>   

**Today's Progress**: Was occupied today, but made sure i didn't skip it. Added pull to refresh loader using UIRefreshControl and loadmore progress at the UITableViewCell footer. Also worked woth Transition when presnting views.

**learnt about** 
- Intro to Transitions
- UIRefreshControl
**Thoughts:**  Was almost tired..

**Link to work:** [tweet](https://twitter.com/myorwah/status/1043048346481582080) 

 

