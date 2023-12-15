All Patch notes for BetterLocomotion because vrcmods has a limit on how many characters you can have in the description

How to setup BetterLocomotion V1.403: https://www.youtube.com/watch?v=friEW95WFfM

How to add custom idles to Better Locomotion V1.403: https://www.youtube.com/watch?v=evk069ajbHY

How to add custom poses to Better Locomotion V1.403: https://www.youtube.com/watch?v=ppGbphDEutE

V1.403
Fixed an issue with the action layer breaking fullbody users. From now on if you're in fullbody, the action layer is completely disabled for you.
Added 2 more idle animations that I see being commonly used
Added another pose in the locomotion (mostly for video tutorial on how to add custom poses)
Fixed every pose that lagged behind when changing height up or down in them
Made a quick script to merge avatar parameters so you don't have to download an external one

V1.402
Added mirroring to idle animations
Added all the default animations for movement in the unitypackage. Now you should never see missing animation in any of the animation states.
For clarity - Default animations are the ones found in the examples folder in the vrcsdk, I simply just copy pasted them into a separate folder

V1.401
Revamped the locomotion logic so that it runs smoother and is easier to understand
Added more action animations in the action layer so that you don't have to setup more animations
Removed unused fly parameter and fly toggle in the menu that was accidentally left in there

V1.400 (HotFix)
Just forgot to put the new standing idle in the Eternal Voyager Idle crouching blend-shape , resulting in the avatar moving backwards when crouching while using it. Since this is a hotfix, the version number stays the same.

V1.400

**NOTE**
I will now be allowing anyone to switch into my Better Locomotion testing bot so they can see my progress on it as I work on it, it won't change very often, but when it does, it gets updated multiple times as it's faster than building it locally

https://vrchat.com/home/avatar/avtr_bfb69f2a-567a-4b13-a839-d7aa75e01b5f

Changelog:
1:	Fixed going from pose to idle animation using the previous idle animation when you reset locomotion

2:	Added lock pose button to lock your pose, this only works on poses, you cannot lock your idle position

3:	Changed the stand still in the idle animation's menu from a toggle to a button, doesn't change anything important, just keeps it consistent with everything else

4:	Added buttons to slowly increase/decrease your height rather than just using the radial to do it, you still have the radial

5:	Completely overhauled all of the pose menu's, it looks and feels much better

6:	Shamelessly stole some icons from GogoLoco and used them in the pose menu (I'm a menace I know)

7:	Changed the stand still idle as the old one acted weird with its left leg for some reason

Known bugs:
	Switching idle animations quickly while in a dance causes that dance to break ; easy fix is to just replay the animation

V1.302
Fixed the default laydown pose animations from breaking the neck when you weren't crouching, also removed an animator controller that was accidentally left behind from the last update :3

Better Locomotion > GogoLoco

V1.301
Fixed seat issues. When you sat down in a seat, the idle animation used to break completely, it does not do this anymore

V1.300
Fix some issues with going from pose to an idle animation, the issue was that when you swapped from pose to idle animation your avatar would freak out, the fix at the time was to click the reset avatar button, now it resets the avatar automatically!
Minor fix to the main menu, when you add the main menu as a submenu the "Better Locomotion made by DamnDanial101" used to not be centered, it now is

V1.2: Added New Idle animation and pose, mainly for a tutorial on how to add your own poses and idle animations, also updated logic in base locomotion so that now when you adjust height without being in a pose it puts you in the default pose, this should be the last update for a while unless someone points out a bug or something (please do point bugs out if you try my locomotion and run into any)

V1.1: Quick update forgot to allow movement of the arms while in pose, new update fixes that and allows quest or pcvr users to move their arms while in a pose

Better Locomotion allows you to switch between idle animations while in the avatar, it also has some sit-down poses as well, it's also super easy to add your own poses and idle animations or to change the existing ones
