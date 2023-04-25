## Email

For executing the functionality of an email `SMTP` simple mail transfer protocol is used.

One more protocol `POP3` is used in combination with `SMTP`.

One is used to `send` emails that are stored in the user's inbox and other is used to `reterieve` emails sent to the users.

`SMTP also used TCP protocol` and its PORT is 25.

## How SMTP works ??

-> When an email is sent it is sent to the sender's SMTP server using SMTP protocol.

-> The SMTP server places the email on a `Messsage Queue`.Then SMTP server initiates a connection with receiver SMTP server and condcuts an initial SMTP handshake.

-> Then finally it sends the email to receiptents SMTP server.

-> The email is downloaded from Receiver SMTP server and then the client shows the mail.

**Note->** If the receiver SMTP server is on the same SMTP server of the sender then it will direct send the email it does not require any connection.

SMTP is a **`Push`** protocol which sends the email.

POP3/IMAP is a **`Pull`** protocol which helps to download the email.

If the receiver SMTP server is`offline`the senders SMTP server tries again and again after some minutes.There is a set time after which it will stops sending the email and marks it not delievered.

## POP -> Post office protocol

It downloads the email in 4 phases.

1-> Connect

2-> Authorize

3-> Transaction

4-> Update

SO the user agent is connected to the POP3 over TCP this is `connect` Phase.Then the` authorization` phase started by using email and password that the user which downloads the email is the valid user or not. Then the `transaction` happens that the user is start going to receieve the messages.

After this the user agent quits and closes this POP3 session.

Finally the server marks as `updated` on all the delievered emails.

Two Modes of POP

1-> Download and Keep

2-> Download and delete

## IMAP Internet Message access protocol

Emails are kept on the server and not deleted local copies of the emails are cahced on each devices.

If an email is deleted by the user manually then only it gets deleted from the server only.
