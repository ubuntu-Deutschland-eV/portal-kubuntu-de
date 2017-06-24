Title: Interview: Tobias König about the development of Akonadi
Date: 2008-03-12 18:16
Author: Monika Eggers
Tags: English
Slug: interview-tobias-konig-about-the-development-of-akonadi

[![Tobias König auf den Chemnitzer-Linux-Tagen 2008 mit Konqui auf der
Schulter](http://wiki.kubuntu-de.org/images/Tobias_Koenig_CLT-2008-klein.jpg){width="220"
height="165"}](http://wiki.kubuntu-de.org/images/Tobias_Koenig_CLT-2008.jpg)

</p>
[kubuntu-de.org in conversation with Tobias König]{.external .text}
===================================================================

</p>
<address>
*Translations are available in:
[Italian](http://www.kde-it.org/news.php?extend.183) (thanks to
kde-it.org) and
[Polish](http://www.kde.org.pl/Wywiady/Tobias_K%C3%B6nig_o_rozwoju_Akonadi)
(thanks to kde.org.pl)* *The german original can be found
[here.](http://www.kubuntu-de.org/nachrichten/sonstiges/interview-tobias-k-nig-ber-die-entwicklung-von-akonadi)*

</address>
</p>
[Tobias
König](http://tokoe-kde.blogspot.com/ "http://tokoe-kde.blogspot.com/"){.external
.text} is a Computer Science student and one of the core developers of
[Akonadi](http://kdepim.kde.org/akonadi/ "http://kdepim.kde.org/akonadi/"){.external
.text}, one of the innovative technologies that will be implemented in
[KDE4](http://www.kde.org/announcements/4.0/ "http://www.kde.org/announcements/4.0/"){.external
.text}. Akonadi will be a platform independent innovative storage
solution for personal data. In this interview, Tobias König shares his
impressions about the integration into the [KDE desktop
environment](http://www.kde.org/ "http://www.kde.org"){.external .text}
and Akonadi's development and features.

</p>
**kubuntu-de.org:** You are deeply integrated into the development of
KDE. What kinds of things do you spend time on when you do not work on
that?

</p>
**Tobias König:** I study Computer Science at the HTW Dresden while I am
not busy with developing KDE. I also work as a freelancer for credativ
GmbH.

</p>
<!--break--><!--break-->

**kubuntu-de.org:** What is credativ GmbH and what are they offering?

</p>
**Tobias König:** Credativ GmbH offers services around open source
software solutions. The majority of coworkers come from the open source
environment, as from the [debian
project](http://www.debian.org/ "http://www.debian.org/"){.external
.text} or from
[postgres](http://www.postgresql.org/ "http://www.postgresql.org/"){.external
.text}. There are also a couple of people from KDE :).

</p>
**kubuntu-de.org:** One could say, you made your hobby your occupation?

</p>
**Tobias König:** Yes, one could say that :). However, I am mainly a
student for the next 2.5 years.

</p>
**kubuntu-de.org:** This means that you are 24/7 busy with open source
packages ;). Could you tell us which KDE projects you are participating
with? For which tasks have you taken responsibilities?

</p>
**Tobias König:** My home is the [KDE-PIM
project](http://kdepim.kde.org/ "http://kdepim.kde.org"){.external
.text}. This is the subproject for KDE which is focused on personal
information management. This encompasses calendars, address books and
e-mails. In addition to the management of KAddressBook, I also help with
the development of Akonadi, the new system for PIM storage. During the
time KDE3 was ported to KDE4, I also supported the development of the
core libraries for KDE.

</p>
**kubuntu-de.org:** Akonadi is a good topic. Could you explain what
Akonadi is in detail? Is it not true, that already now, there are too
many groupware solutions, all promising to deal was any possible data
types?

</p>
**Tobias König:** At first the most important: Akonadi is not a
groupware server! In contrast, Akonadi is an intermediate storage and
abstraction layer for PIM data. This is similar to Phonon, for
multimedia or Solid for hardware. Akonadi abstracts the access and
maintenance of data for the rest of the system (i.e. the address book or
the calendar). This is achieved by offering a common interface for all
the data. In turn there are several improvements in comparison to KDE3:
1. PIM data must only be held once in the memory 2. There is a central
instance which monitors any change of the data and hence informs all
other components about it. 3. The whole Akonadi framework follows an
asynchronous communication design. This means blocking of the user
interface or for the loading or storing of data cannot occur anymore.

</p>
**kubuntu-de.org:** That is already quite a lot. As I understand this,
the access to the PIM data will be easier, faster and more efficient.
How will this affect the normal user? The possibility for multiple
applications to access the same resource existed already in KDE3. As an
example, Kopete and Konversation can synchronise contacts. What is the
difference to this?

</p>
**Tobias König:** The user will benefit from Akonadi due to the
avoidance of inconsistencies between the different presentations of the
data in the different applications of the desktop. If a contact in the
address book is changed, it automatically updates the birthdays in
Plasmoid. The memory usage decreases since the data is only held once in
memory.

</p>
It will also be possible to integrate PIM data into other KDE
applications in a better way. In addition to a users name, his image
could be shown in the properties dialogue for a file. The components
that communicate the data between the Akonadi server and the data source
(i.e. a groupware server) are distributed into separate processes. This
protects the system from a crash of a component due to bugs in badly
developed software. The crashed component can just be restarted and the
data will be re-loaded..

</p>
**kubuntu-de.org:** This smells a lot like innovation! Will Akonadi also
obtain new or better resource types?

</p>
**Tobias König:** The main task will be to port the existing resource
type into Akonadi. The clean and asynchronous interfaces shall increase
the liability of the resources. At the moment, there is work on a
resource allowing access to MS Exchange. The developer or the
alternative KDE email client Mailody also develops a resource, which
will allow direct access to IMAP. This means that the KDE client for the
Kolab groupware server is not dependent on KMail any more, but Akonadi
can communicate directly with the Kolab server.

</p>
**kubuntu-de.org:** Will this be implemented in KDE 4.1?

</p>
**Tobias König:** KDE 4.1 will include Akonadi as a developer platform.
This means that the APIs will be stable and the service is usable.
However, not all PIM clients will use Akonadi yet due to missing
developer resources.

</p>
**kubuntu-de.org:** Will KDE4-PIM be based from the beginning on
Akonadi?

</p>
**Tobias König:** Yes, but we have also planned for a migration path
that will allow to integrate the old resource framework into Akonadi, or
allow Akonadi to access the old resources framework.

</p>
**kubuntu-de.org:** How can someone get involved into the Akonadi
development?

</p>
**Tobias König:** One can just contact the KDE PIM developers via the
email address <kde-pim@kde.org>, or via the \#kontakt channel.
Especially the porting of a couple of resources for the Akonadi API
should be an easy entry into the world of Akonadi.

</p>
**kubuntu-de.org:** The development of Akonadi has been for some time
... mmmh ... slow. What have you planned in the next time to make up for
the lost time?

</p>
**Tobias König:** The slow progress in the development is merely caused
by the lack of developers. At the moment, the main development tasks are
performed by 3-4 developers (I want to point out in particular the
efforts of Volker Krause. Without him the project would probably already
be suspended). Two of them work full time, the other two study or write
their thesis. This means that only the evenings or developer meetings
are available for the hacking. Apropos developer meetings: During the
Easter weekend, there will be a Akonadi hacking meeting in the KDAB
offices in Berlin. There, we will double check and improve the API once
more. In April will be the API freeze. Hopefully, we will find some time
to also implement some of the missing features (maybe we will even hide
some Easter eggs :)).

</p>
**kubuntu-de.org:** This sounds very exiting and innovative.
Kubuntu-users are especially interested in the following: Which
distribution do you use?

</p>
**Tobias König:** Debian unstable ;). This has historical reasons. At
the time when I set up my systems, Ubuntu did not exist yet. Since then,
it was not necessary for me to re-install my systems :).

</p>
**kubuntu-de.org:** Do you already use KDE4 for your daily work? If so,
how satisfied are you so far?

</p>
**Tobias König:** Yes, I already use KDE4 for about 3 months. At the
beginning, it was irritating that the Plasma desktop had problems every
two days. However, it is stable now, and it is possible to work on it.

</p>
**kubuntu-de.org:** Is there anything else you want to communicate to
the world?

</p>
**Tobias König:** Akonadi rocks! :)

</p>
**kubuntu-de.org:** Thank you for this window into the development of
Akonadi. We are exited about the innovations! Thanks for the interview!

</p>
**Tobias König:** You are welcome. It was a pleasure! :)

</p>

