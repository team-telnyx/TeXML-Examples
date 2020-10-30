This script forwards an inbound call to a number (you can also set this up to be forwarded to a sip uri) and if the call fails it sends it to a voicemail.

When the call fails, the script plays a recording that can be any greeting that's accesible online as an mp3 file. And then plays a beep signaling the script is now recording.

Once the recording is finished you'll get a webhook to the specified destination. In that webhook you'll get the address of where the voicemail is stored.

Hint, since calls between Telnyx numbers in the same account are free, you can set this up to enable voicemail for any number in your account and you'll only get charged for the use of the TeXML but not for the call. This way you can activate a voicemail option whenever you are not able to answer your Telnyx numbers.
