# sftp-messager
Just my tries, don't try understand this

Based on OpenSSH SFTP protocol. 

Okay, how use it:
1. Make SFTP server.

    1.1. I recommend: DISABLE password auth, DISABLE root logon and change standart port. Also use encrypted auth keys.

    1.2. In user home directory must exist `messages.json` file with content `{}`

2. Setup config.py

    2.1. To check config - run it by python interpreter

- Linux/GNU: works.
- Termux (Android): not work.

I can't be sure that this will work on other systems.


P.s.: I use Arch btw
