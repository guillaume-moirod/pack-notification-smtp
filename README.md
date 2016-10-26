pack-smtp-email-notification
============================

This pack contain some command and notifiationway to allow us to send
email using an SMTP server.

For configuring smtp credential you have to edit resource.d/smtp.cfg
file

```
$SMTP_HOST$=localhost
$SMTP_USERNAME$=shinken@example.com
$SMTP_PASSWORD$=myP@ssW0rd
$SMTP_SENDER_EMAIL$=monitoring@example.com
```

Usage
=====

This pak add a new notificationway named smtp-email. You can configure
your users to use it.
