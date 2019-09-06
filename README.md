# Recreating-WeChat

This is a messaging app that recreates WeChat using Google sign-in and Firebase. To user it, the user will first sign in with a Google account. If the user already have friends added before, he or she can directly select on a friend and start/continue a conversation. If the user is new or wants to add a new friend, he or she can go to "Contacts" and, select the "Add" button at top, enter the friend's username in the search bar and then choose the friend from related results. At this point if the user goes back to "Chats", he or she will find the new friend in the chat list. The most recent message of a chat will be shown under the friend's name.

To solve the problem of real-time data renewal on the UI, the app implements timers to regularly request updated information (e.g. chat list, message list) from Firebase and refresh the view accordingly.

Possible features of this project in the future: Photo/voice message, new message notification, read/unread mark...
<br><br>
# Screenshots
<br><img src="https://github.com/RichieZhu26/Recreating-WeChat/blob/master/screenshot/signin.jpeg" width="400">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/RichieZhu26/Recreating-WeChat/blob/master/screenshot/chat.jpeg" width="400">
<br><br><img src="https://github.com/RichieZhu26/Recreating-WeChat/blob/master/screenshot/contact.jpeg" width="400">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/RichieZhu26/Recreating-WeChat/blob/master/screenshot/search.jpeg" width="400">
<br><br><img src="https://github.com/RichieZhu26/Recreating-WeChat/blob/master/screenshot/message.jpeg" width="400">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/RichieZhu26/Recreating-WeChat/blob/master/screenshot/send.jpeg" width="400">
