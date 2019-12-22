#  ShowLoginWindow

A very simple Mac app that shows the login window. It should be identical to a user using the fast user switching menu and choosing "Login Window…". Useful if you want to show the login window without that menu being visible.

Uses the private `SACShowLoginWindow` method from `/System/Library/PrivateFrameworks/login.framework`, so it might not work in the future. Tested on 10.15.2.
