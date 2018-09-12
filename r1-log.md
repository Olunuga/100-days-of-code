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
[ ]convert location to using lat and long


**learnt about** 
- Date compasrism
- Date components.

**Thoughts:** Couldn't test the app on my device because i back dated the phone which cause debug profile to fail and somehow couldnt do it on emulator too : this is kinda crazy though.

**Link to work:** [tweet](https://twitter.com/myorwah/status/1039740897490075648) 





