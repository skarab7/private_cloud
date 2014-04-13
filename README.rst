Paranoid Startup Bundle
============================

Requirements
=================

Functional
--------------

- Secure Messager replacement
- Secure Voice-Calls replacement
- Secure data share 

Non-functional
----------------

- easy setup (sharing link to get into it)
- simple way to include friends to the private cloud (growing friends)
- in one, easy to consume package
- end-to-end encryption
- support MacOs and linux

Solution
===============

Remote-side
-------------

+----------+--------------------------+-----------------+
|          | Category                 | Replacement     | 
+----------+--------------------------+-----------------+
| skype    | Voice-Calls              | Openfire        |
+----------+--------------------------+-----------------+
| messager | Chat                     | Openfire        |
+----------+--------------------------+-----------------+
| dropbox  | Data share               | Bittorrent-Sync |
+----------+--------------------------+-----------------+

Client-side
-------------

+------------+--------------------------+----------------------------------------+
|            | Category                 | Replacement                            |
+------------+--------------------------+----------------------------------------+
|  Messanger | Chat                     | PSI + gpg and OTR plugin               |
+------------+--------------------------+----------------------------------------+
|    skype   | Voice-Calls              | Jitsi with Zrtp [1]                    |
+------------+--------------------------+----------------------------------------+
| dropbox    | Data share               | Bittorrent-Sync + file-level-encyption |
+------------+--------------------------+----------------------------------------+


[1] https://jitsi.org/Documentation/ZrtpFAQ

Architecture
==============

- a
- b
- c

Realization
=============

- ansible
- fabric
- salt
  
