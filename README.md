# colorblind-lcd
An LCD config file for red-green colorblindness 

I've only tested this on my MacBook Pro (15-inch, Late 2011) with anti glare screen.

##Notice:

I am not a doctor or health professional, and I am red-green colorblind so disclaimer:
**This product is not intended to diagnose, treat, cure, or prevent any disease.**

Does this help people with red-green colorblindness see things on their screen better?
I'd like to think so, but I really don't know.

Also, note that color blindness varies from person to person, so even if this really 
does "help" me, there's no guarantee that the precise balance of rods and cones and 
stuff in your or anyone else's eyes is similar. Could even cause eyestrain or something, 
I really don't know.

##To Install

Copy the `.icc` file into one of the following:
```
# For all users
/Library/ColorSync/Profiles

# For a single user
/Users/[username goes here]/Library/ColorSync/Profiles/

# For only the current user
~/Library/ColorSync/Profiles/
```

Next, select the profile in:
```
System Preferences » Displays » Color
```
