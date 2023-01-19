# Lab01_Web
Internet before the Web experience.

jdgomez@Latitude3400JDgomez:/mnt/c/Users/jdgom$ telnet telehack.com
Trying 64.13.139.230...
Connected to telehack.com.
Escape character is '^]'.

Connected to TELEHACK port 115

It is 10:03 am on Thursday, January 19, 2023 in Mountain View, California, USA.
There are 77 local users. There are 26647 hosts on the network.

  Type HELP for a detailed command list.
  Type NEWUSER to create an account.

May the command line live forever.

Command, one of the following:
  2048         ?            ac           advent       aquarium     basic
  bf           c8           cal          calc         callsign     ching
  clock        cowsay       date         ddate        delta        diff
  dir          exit         factor       file         finger       fnord
  geoip        gif          head         ipaddr       joke         liff
  login        more         morse        netstat      notes        octopus
  phoon        pig          pong         primes       privacy      qr
  rain         rand         rig          rot13        run          salvo
  tail         traceroute   typespeed    uptime       usenet       users
  uumap        uupath       uuplot       weather      when         zc

Press control-C to interrupt any command.
More commands become available after login.

# 01) ¿Cómo pide auxilio una vaca paranoica? (10 puntos)
.cowsay /paranoic help
 ______
< help >
 ------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

# 02) En zork, ¿qué hay al subir las gradas dentro de la casa? (50 puntos)

.zork
ZORK

Welcome to ZORK.
Release 13 / Serial number 040826 / Inform v6.14 Library 6/7
West of House
This is an open field west of a white house, with a boarded front door.
There is a small mailbox here.
A rubber mat saying 'Welcome to Zork!' lies by the door.

>north
North of House
You are facing the north side of a white house.  There is no door here,
and all the windows are barred.

>east
Behind House
You are behind the white house.  In one corner of the house there is a
small window which is slightly ajar.

>open window
With great effort, you open the window far enough to allow entry.

>enter
Kitchen
You are in the kitchen of the white house.  A table seems to have been
used recently for the preparation of food.  A passage leads to the west
and a dark staircase can be seen leading upward.  To the east is a small
window which is open.
On the table is an elongated brown sack, smelling of hot peppers.
A bottle is sitting on the table.
The glass bottle contains:
 A quantity of water

>east
Behind House

>west
Kitchen
You are in the kitchen of the white house.  A table seems to have been
used recently for the preparation of food.  A passage leads to the west
and a dark staircase can be seen leading upward.  To the east is a small
window which is open.
On the table is an elongated brown sack, smelling of hot peppers.
A bottle is sitting on the table.
The glass bottle contains:
 A quantity of water

>west
Living Room
You are in the living room.  There is a door to the east, a wooden door
with strange gothic lettering to the west, which appears to be nailed
shut, and a large oriental rug in the center of the room.
There is a trophy case here.
A battery-powered brass lantern is on the trophy case.
There is an issue of US NEWS & DUNGEON REPORT dated 08/26/04 here.
On hooks above the mantelpiece hangs an elvish sword of great antiquity.

>take lantern
Taken.

>turn on lantern
The lamp is now on.

>east
Kitchen
You are in the kitchen of the white house.  A table seems to have been
used recently for the preparation of food.  A passage leads to the west
and a dark staircase can be seen leading upward.  To the east is a small
window which is open.
On the table is an elongated brown sack, smelling of hot peppers.
A bottle is sitting on the table.
The glass bottle contains:
 A quantity of water

>up
Attic
This is the attic. The only exit is stairs that lead down.
There is a square brick here which feels like clay.
A large coil of rope is lying in the corner.
On a table is a nasty-looking knife.

# 03) ¿Cuál es el output de éste programa de Brainf*ck (20 puntos)

.bf ++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
[bf] Executing as Brainfuck code...
Hello World!

# 04) Copien el titulo, la fecha de publicación y el primer parrafo de dos de los siguientes rfc históricos (20 puntos): 318,675,791,793,819,1034,1855,2324

- 318 -
Title: Telnet Protocol
Date: April 3, 1972
First Paraphrase: At the October 1971 Network Working Group Meeting, I promised to
promptly produce a document which clearly and succinctly specified
and explained the Official Telnet Protocol.  This document fails to
meet any part of that promise.  This document was not produced
promptly.  This document is neither clear nor succinct.  There is NO
Official Telnet Protocol.

- 675 -
Title: SPECIFICATION OF INTERNET TRANSMISSION CONTROL PROGRAM
Date: December 1974
First Paraphrase: INTRODUCTION
This document describes the functions to be performed by the
internetwork Transmission Control Program [TCP] and its interface to
programs or users that require its services. Several basic
assumptions are made about process to process communication and these
are listed here without further justification. The interested reader
is referred to [CEKA74, TOML74, BELS74, DALA74, SUNS74] for further
discussion.

- 791 -
Title: INTERNET PROTOCOL
Date: September 1981
First Paraphrase: prepared for
Defense Advanced Research Projects Agency
Information Processing Techniques Office
            1400 Wilson Boulevard
        Arlington, Virginia  22209
                by
    Information Sciences Institute
University of Southern California
        4676 Admiralty Way
Marina del Rey, California  90291

- 793 -
Title: TRANSMISSION CONTROL PROTOCOL
Date: September 1981
First Paraphrase: prepared for
Defense Advanced Research Projects Agency
Information Processing Techniques Office
            1400 Wilson Boulevard
        Arlington, Virginia  22209
                by
    Information Sciences Institute
University of Southern California
        4676 Admiralty Way
Marina del Rey, California  90291

- 819 -
Title: The Domain Naming Convention for Internet User Applications
Date: August 1982
First Paraphrase: Introduction
For many years, the naming convention "<user>@<host>" has served the
ARPANET user community for its mail system, and the substring
"<host>" has been used for other applications such as file transfer
(FTP) and terminal access (Telnet).  With the advent of network
interconnection, this naming convention needs to be generalized to
accommodate internetworking.  A decision has recently been reached to
replace the simple name field, "<host>", by a composite name field,
"<domain>" [2].  This note is an attempt to clarify this generalized
naming convention, the Internet Naming Convention, and to explore the
implications of its adoption for Internet name service and user
applications.

- 1034 -
Title: DOMAIN NAMES - CONCEPTS AND FACILITIES
Date: November 1987
First Paraphrase: STATUS OF THIS MEMO
This RFC is an introduction to the Domain Name System (DNS), and omits
many details which can be found in a companion RFC, "Domain Names -
Implementation and Specification" [RFC-1035].  That RFC assumes that the
reader is familiar with the concepts discussed in this memo.

- 1855 -
Title: Netiquette Guidelines
Date: October 1995
First Paraphrase: Status of This Memo
This memo provides information for the Internet community.  This memo
does not specify an Internet standard of any kind.  Distribution of
this memo is unlimited.

- 2324 -
Title: Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0)
Date: 1 April 1998
First Paraphrase: Status of this Memo
This memo provides information for the Internet community.  It does
not specify an Internet standard of any kind.  Distribution of this
memo is unlimited.
