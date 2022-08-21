# MyBB stuffs, v3rm edition.

tid = thread id, for example; https://v3rmillion.net/showthread.php?tid="1184895"

pid = post id, for example; https://v3rmillion.net/showthread.php?pid=8344660#pid"8344660"

uid = user id, for example; https://v3rmillion.net/member.php?action=profile&uid="2386065"

fid = forum/section id, for example; https://v3rmillion.net/forumdisplay.php?fid=3

rid = reputation id, not sure on this one. no example.

bburl = link to DMs I'dassume.

can execute either in console or with "javascript:" method. (javascript:MyBB . . .) in search bar.

MyBB.whoPosted(tid) shows users that posted the most comments in that thread. Looks like this: https://media.discordapp.net/attachments/1000447120261791834/1010916645243457647/unknown.png

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

HTMLchars: ƒ (text)

changeLanguage: ƒ ()

changeTheme: ƒ ()

deleteAnnouncement: ƒ (data)

deleteEvent: ƒ (eid)

deleteReputation: ƒ (uid,rid)

detectDSTChange: ƒ (timezone_with_dst)

dismissPMNotice: ƒ (bburl)

forumMarkedRead: ƒ (fid,request)

init: ƒ ()

markForumRead: ƒ (event)

pageLoaded: ƒ ()

popupWindow: ƒ (url,options,root)

reputation: ƒ (uid,pid)

select2: ƒ ()

submitReputation: ƒ (uid,pid,del)

unHTMLchars: ƒ (text)

viewNotes: ƒ (uid)

whoPosted: ƒ (tid)
