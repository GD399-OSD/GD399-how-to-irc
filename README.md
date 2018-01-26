# How to IRC
### What the hell is IRC?

Internet Relay Chat (IRC) is a networked, decentralized chat service consisting of various Networks and Servers. It has been used by the open source community to organize, chat, and theorize for many years, and is baked into the fabric of open source technology and philosophies.

### Why the hell are we using it?

We'll be using a class IRC channel in addition to GitHub Issues to ask questions, answer questions, and chat about things related to class and open-source things in general. The hope is that doing everything, even online chat, in an open-source way, will teach us something about the potential value of forgotten and potentially arcane technologies.

---

### How the hell do I use it?

This is the fun part (maybe). There are many ways to connect to IRC: using a web client, a desktop client, using TOR, or any other number of weird things. __We'll focus on the easy one.__

#### Basic Info
__Channel Name:__ `#GD399-OSD` — This is the name of the "channel" we will use for chat.

__Channel Owners & Ops__: Devin and Kristian — An "Op" is a channel operator, who can kick roudy people out of the channel. Infinite power.) Really, this just ensures the channel won't be deleted.

#### Registering Yourself
- [ ] In your browser of choice, navigate to https://webchat.freenode.net/. This is a *web client* that allows you to collect to the *Freenode Network*, which is an IRC network meant exclusively for the discussion of open source things like OSS and open organizations.

![Freenode entrance](Images/1.png?raw=true "Freenode entrance")

- [ ] Enter a *nickname*. This is what you will go by in our IRC Channel, like a Twitter handle. I suggest using your first and last name, all lowercase, like this: `devinhalladay`.
- [ ] In the `Channels` field, enter `#GD399-OSD`. This is the name of the IRC Channel just for our class.
- [ ] You can ignore the `Auth to services` checkbox. Skip to the `Humanity` captcha.
- [ ] Verify you're not a robot (or are you...?) and click "Connect".
- [ ] *Register* your nickname so others can't take it. To do this, type `/msg NickServ register password email` into the text box at the bottom and hit enter. Replace `password` with the password you want to use and replace `email` with the email you want to receive a message at. You'll get an email with a new message to send that verifies your identity.

![Freenode verification](Images/2.png?raw=true "Freenode verification")

6. Copy the command, paste it into the message box, and hit enter. You're registered now! Nice.

---

#### Logging In ("Identifying" Yourself)
- [ ] Every time you connect from now on, you'll need to *"Identify"* yourself so the server knows you're really you. Type `/msg NickServ identify password` (replace `password` with the password you chose while registering) and hit enter, and you should now be identified as a legit user of your chosen nickname.

---

#### Direct Messaging

IRC has a simple direct messaging system that allows you to chat privately with a specific user. Here's how to use it:

- [ ] Type the command `/msg username message`, where `username` is your username and `message` is your message. For example, `/msg devinhalladay Hi!`.

![Freenode DM](Images/3.png?raw=true "Freenode DM")

- [ ] You should now see a tab in the top of the webpage. Click on it and chat away!

---

#### Other Things

- If you choose a nickname that happens to be taken, change your nickname to something else by sending the message `/nick [new_nickname]`
- If you want more info on IRC, here are some good reads:
  - [Freenode's Philosophy](http://freenode.net/philosophy)
  - [What is the Freenode Project?](http://freenode.net/project)
  - [IRC Help](http://www.irchelp.org/) — Lots of good info on IRC, and commands you can run.
