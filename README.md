# MyBB stuffs, v3rm edition.

tid = thread id, for example; https://v3rmillion.net/showthread.php?tid="1184895"

tid = tracking id

pid = post id, for example; https://v3rmillion.net/showthread.php?pid=8344660#pid"8344660"

uid = user id, for example; https://v3rmillion.net/member.php?action=profile&uid="2386065"

fid = forum/section id, for example; https://v3rmillion.net/forumdisplay.php?fid=3

rid = reputation id, not sure on this one. no example.

eid = event id, not sure what this does.

aid = app id

el = event label

ev = event value

ea = event action

e = event

sn = social network

sa = social action

expid = xid

bburl = link to DMs I'dassume.

can execute either in console or with "javascript:" method. (javascript:MyBB . . .) in search bar.

# How do I get my postkey?

NOT IMPORTANT/NEEDED UNLESS DOING "MISC"

![unknow123213n](https://user-images.githubusercontent.com/83344789/185798306-9c14532a-2215-4e01-af04-01d34c7b7d0b.png)

MyBB.whoPosted(tid) shows users that posted the most comments in that thread. Looks like this: 
![image](https://user-images.githubusercontent.com/83344789/185798342-0f9f1919-40bf-4dda-88b2-63ceb0172167.png)

MyBB.reputation(uid) shows the rate/reputation page, does exactly the same as pressing "Rate" on a user's profile.

MyBB.markForumRead() don't quite know how to use this.

MyBB.viewNotes(uid) displays user notes. I do not have access to UserCP so I can not demonstrate this.

MyBB.viewNotes() displays this; MyBB.popupWindow("/reputation.php?action=add&uid="+uid+"&pid="+pid+"&modal=1");},viewNotes:function(uid), full link goes to here: https://v3rmillion.net/reputation.php?action=add&uid=%22+uid+%22&pid=%22+pid+%22&modal=1%22);},viewNotes:function(uid)

MyBB.deleteReputation(uid) self explanatory.

MyBB.pageLoaded() self explanatory.

MyBB.init() checks if pageLoaded

MyBB.valueOf() shows all values of prototypes.

MyBB.changeTheme() self explanatory.

MyBB.dismissPMNotice(bburl) auto reads/dismisses PM notifications.

MyBB.popupWindow(url, options, root) self explanatory.

# broken

MyBB.unHTMLchars()

# values

HTMLchars: ?? (text)

changeLanguage: ?? ()

changeTheme: ?? ()

deleteAnnouncement: ?? (data)

deleteEvent: ?? (eid)

deleteReputation: ?? (uid,rid)

detectDSTChange: ?? (timezone_with_dst)

dismissPMNotice: ?? (bburl)

forumMarkedRead: ?? (fid,request)

init: ?? ()

markForumRead: ?? (event)

pageLoaded: ?? ()

popupWindow: ?? (url,options,root)

reputation: ?? (uid,pid)

select2: ?? ()

submitReputation: ?? (uid,pid,del)

unHTMLchars: ?? (text)

viewNotes: ?? (uid)

whoPosted: ?? (tid)

#thread

### thread is self explanatory, all ids are above.

also works with javascript:

clearMultiQuoted: ?? ()

deletePost: ?? (pid)

init: ?? ()

initMultiQuote: ?? ()

initQuickReply: ?? ()

loadMultiQuoted: ?? ()

multiQuote: ?? (pid)

multiQuotedLoaded: ?? (request)

quickEdit: ?? (el)

quickReply: ?? (e)

quickReplyDone: ?? (request,status)

restorePost: ?? (pid)

showIgnoredPost: ?? (pid)

viewNotes: ?? (tid)

# report

reportReputation(pid) almost unusable.

reportPost(pid)

reportUser(pid)

reportError()

init: ?? ()

reportPost: ?? (pid)

reportReputation: ?? (pid)

reportUser: ?? (pid)

submitReport: ?? (pid)

# misc

https://v3rmillion.net/alerts.php?action=delete_all&my_post_key= ENTER POSTKEY HERE &ret_link=https%3A%2F%2Fv3rmillion.net%2Fforumdisplay.php%3Ffid%3D11
