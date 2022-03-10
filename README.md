# post-notifier
This projects aim is to notify the receiver if mail was received. The receiver will be automatically chosen.
## Motivation and Context
Soon the NGO i am involved with will habit at bUm in Berlin. Mail that receives the bUm are gathered in one place. To notify the receiver, i want to build this project.
## What this projects needs to be able to do:
1. An ESP32 needs to tell a Pi, which receiver was manually chosen
2. The receiver will be notified via email
3. Even if manually chosen, a receiver won't be notified again until
4. the receiver confirms that he accepted his mail
5. the receiver can be notified again.
### How the receiver will be chosen
- An embedded system will be placed where the
