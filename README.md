geektalkd

---

geektalkd is a simple chat server designed for use with thin clients (like telnet, netcat, or one of the avaliable perl clients). It features multiple channels, private whispers, and everything else you'd expect from a chat server. Additionally, all of the parser code can be rewritten and reread, so you can install new functions on the fly, without restarting the server, or kicking users off.

* Version 1.24 includes features for access control lists to restrict users to certain domains. This is version 1.25.

* News: geektalkd was featured in the [March 2003] issue of [Linux Journal]!! Nuts! You can [read the article online].


Here is the [readme] file and the official repository at [geektalk.org].


A sample help screen (to give you an idea of the featureset):

```
* Geektalk Help:
*   /bye or /quit                     quit from geektalk
*   /signon [<channel #>]             signon to geektalk session
*   /signoff                          signoff from geektalk session
*   /channel [<channel #>]            show/change channel
*   /invite <user>                    invite <user> to your channel
*   /names [<user>]                   list users
*   /stats [<user>]                   get various statistics
*   /ping <user>                      send a 'beep' to <user>
*   /tell <user> <msg>                send a message to <user>
*   /ignore [<user> [on|off|0|1]]     start or stop ignoring a user
*   /disregard [<user [on|off|0|1]]   start or stop disregarding a user
*   /times [on|off|1|0]               turn timestamping of messages on/off
*   /echo [on|off|1|0]                turn echoing of your own message on/off
*   /me <message>                     do an action ("/me eats bl00d.")
*   /nuclear <message>                print something anonymously
*   /username <username>              change your username
```


[Linux Journal]: <http://www.linuxjournal.com/> "Linux Journal"
[March 2003]: <http://www.linuxjournal.com/lj-issues/issue107/> "March 2003"
[read the article online]: <http://www.linuxjournal.com/article.php?sid=6489> "read the article online"

[readme]: <README> "README"
[geektalk.org]: <http://geektalk.org> "geektalk.org"
