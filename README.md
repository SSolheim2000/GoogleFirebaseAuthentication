# GoogleFirebaseAuthentication

This adds Google signin and signout authentication to this Brew Crew demo: 
https://www.youtube.com/watch?v=sfA3NWDBPZ4&list=PL4cUxeGkcC9j--TKIdkb3ISfRbJeJYQwC

One thing to watch out for is that most Google/Firebase/Flutter examples you will see only logout/signout of Firebase using something like this: `_auth.signOut();` or `FirebaseAuth.instance.signOut();`

However, to log out / sign out of Google, you need to use this line too: `_googleSignIn.disconnect();`

If you find this helpful, consider donating $10 to https://teamsolheim.org.
