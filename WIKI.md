botsky

- spellcheck bot
- discussion bot: join to any discussions

- integrations: Twitter, Google Calendar/Microsoft Outlook Calendar, Jira Server Alerts (Legacy), Github/Gitlab/BitBucket, Zoom, Dropbox/GDrive,OneDrive, Google Docs.




=foreign-lang-study(rand questions, level, freaq, day stats)
=Question-answer pairs with any content will be saved in db. Service handles a new received payload with question by rating all Space related questions throught nlp analysis/elastic 'like this' query.
If there is a question with a higher 80 percent occurance it will be sent as an answer.
If there is a question with a higher 50 percent occurance it will be sent as an likely answer.
In other cases there is no suitable answer.






mute
start a call
set a reminder
-
create an event
create a task
create a poll

follow/unfollow message thread
mark unread
pin to channel
set a reminder
-
create a task
create a poll


workspace { ..., webhooks: [] }
channel: settings + set a routine { action: call|live|email|rss|own, schedule, thread })




Integrations(shortcuts menu + message shortcuts + slash commands)
Bots(accessed threads + own dm)
-assistantBot
	- knowledge base(hook all messages in avail channels, @username...answer)
	- reminders(set in avail channels by mention|messageShortcuts, notify in dm, once or periodicaly)
-statsBot(thread mention + dm, snapshots)
-moderatorBot
	-stoplist
	-anti-flooding
	-poster-rating
taskBot(run until done, statusses, dm tasks)
trendsBot?

- email
- rss/twitter/youtube


Perform actions?
routines






http://nodemailer.com/extras/smtp-server/
