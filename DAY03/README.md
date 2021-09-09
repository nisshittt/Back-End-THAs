/////------------------------- [ CHAT APPLICATION ] ----------------------/////

COMMAND PROMT 1:

Subscriber:

SUBCRIBE <channel_name>
SUBSCRIBE  devsnest


COMMAND PROMT 2:

Publisher:

PUBLISH <channel_name> <message>
PUBLISH  devsnest  hello


COMMAND PROMT 1:

Subscriber:

(1) "message"
(2) "devsnest"
(3) "hello"

COMMAND PROMT 3:

Subscriber:

SUBCRIBE <channel_name>
SUBSCRIBE  devs


COMMAND PROMT 2:

Publisher:

PUBLISH <channel_name> <message>
PUBLISH  devs hello


COMMAND PROMT 1:

Subscriber:

(1) "message"
(2) "devs"
(3) "hello"


