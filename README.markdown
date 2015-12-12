This is a bare bones example of how to use Android IPC binders from native C++
code. For some high-level explanations see the following two blog posts:

February 12th, 2014 at 10:52	| #8 Reply | Quote
There are couple minor modifications required to make it work on latest KitKat:
– LOGD macro is now ALOGD
– text output is now under #include , not in utils
– frameworks/native/include has to be added to LOCAL_C_INCLUDES
Thank you for the great example!

- http://ebixio.com/blog/2012/07/07/using-android-ipc-binders-from-native-code/
- http://ebixio.com/blog/2011/01/03/the-android-ipc-system/

The code in this project is Copyright(C) by Gabriel Burca and released under the GPL (http://www.gnu.org/copyleft/gpl.html) license.
