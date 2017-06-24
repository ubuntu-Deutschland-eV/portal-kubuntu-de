Title: KDE 4.0 released - Packages for Kubuntu available
Date: 2008-02-11 12:10
Author: Monika Eggers
Tags: English
Slug: kde-40-released-packages-for-kubuntu-available

[![Bild:KDE.png](http://wiki.kubuntu-de.org/images/Kde.png){width="100"
height="100"}](http://wiki.kubuntu-de.org/images/Kde.png "Bild:KDE4-Plasma.png"){.image}

</p>
[ A Vision Becomes Reality]{.mw-headline}
=========================================

</p>
Today, the KDE developers have as planned the first stable version of
KDE 4.0 released. This release marks the start of the KDE 4 era. The
desktop environment was given groundbreaking changes and improvements.
More about this will be mentioned later in this article. The Kubuntu
developers have made available packages for the releases 7.04 Gutsy
Gibbons and 8.04 Hardy Heron.

</p>
After years of intensive development and with several month delay, the
dream of the [KDE
community](http://www.kde.org/ "http://www.kde.org"){.external .text}
has become reality: KDE 4.0 has finally been released. The demands put
on the entirely redesigned desktop are very high: All in all a
revolution in the desktop area has been aimed for. Nevertheless, it
would be wrong to expect too much from the newly released Version 4.0
due to the fact that several exciting features for the desktop
environment have not been fully implemented yet. Therefore, it must be
stressed that KDE 4.0 is not KDE 4 as the developer Stephan Binner aka
beineri writes in [his
blog](http://www.kdedevelopers.org/node/3174 "http://www.kdedevelopers.org/node/3174"){.external
.text}, but it is rather the beginning of a yearlong continuing set of
release cycle interations.

</p>
### [![Bild:KDE4-Plasma.png](http://wiki.kubuntu-de.org/images/KDE4-Plasma.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Plasma.png "Bild:KDE4-Plasma.png"){.image} [![Bild:KDE4-Plasma2.png](http://wiki.kubuntu-de.org/images/KDE4-Plasma2.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Plasma2.png "Bild:KDE4-Plasma2.png"){.image}[![Bild:KDE4-Konqueror.png](http://wiki.kubuntu-de.org/images/KDE4-Konqueror.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Konqueror.png "KDE4-Konqueror.png"){.image} {#bildkde4-plasma.png-bildkde4-plasma2.pngbildkde4-konqueror.png align="center"}

</p>
<address>
**Note:** Das Original in deutsch ist
[hier](http://www.kubuntu-de.org/nachrichten/software/kde/kde-4-0-mit-kubuntu-paketen-erschienen)
zu finden ( The german original could be found
[here.](http://www.kubuntu-de.org/nachrichten/software/kde/kde-4-0-mit-kubuntu-paketen-erschienen))

</address>
</p>
<!--break--><!--break-->

[]{#For_Everybody_Who_Cannot_Wait:_The_Installation_of_KDE_4.0_under_Gutsy_Gibbon}

</p>
[ For Everybody Who Cannot Wait: The Installation of KDE 4.0 under Gutsy Gibbon]{.mw-headline}
----------------------------------------------------------------------------------------------

</p>
There are already packages available for 7.10 Gutsy Gibbon and the
current development version (8.04 Hardy Herron)

</p>
Since KDE 4.0 is installed into the directory /usr/lib/kde4, it is
possible to install it next to the existing KDE3 installation. A test
without installation can be achived with the KDE 4 [Live
CD](http://cdimage.ubuntu.com/kubuntu/releases/gutsy/kde4/ "http://cdimage.ubuntu.com/kubuntu/releases/gutsy/kde4/"){.external
.text}.

</p>
Instructions:

</p>
-   Remove previous KDE 4 packages, they are not compatible (apt-get
    remove kdelibs5 kde4base-data kde4libs-data)

</p>
-   Add deb <http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu> gutsy
    main to your /etc/apt/sources.list

</p>
-   Install kde4-core, note that PPAs aren't authenticated so you will
    likely get a warning when installing

</p>
-   KDE 4 apps should appear in your KDE 3 K-menu or you can run a full
    session by selecting "KDE 4" from your login manager.

</p>
-   To avoid having to start a second X server for a full session
    install xserver-xephyr and run Xephyr :1 then and run
    /usr/lib/kde4/bin/startkde in the Xerphyr xterm.

</p>
[]{#A_Summary_of_the_Most_Important_Changes}

</p>
[ A Summary of the Most Important Changes]{.mw-headline}
--------------------------------------------------------

</p>
The most obvious change are the new window decorations and the new icon
set: Oxygen follows the guidelines of the freedesktop.org project. This
allows a uniform, consistent and excellent look and feel of the new
desktop environment Plasma. Plasma also provides a new panel and allows
the start-up of a multitude of small applications called widgets.

</p>
In addition, there are numerous small and bigger changes on the desktop
environment: There is a new dialogue for the opening of files. Dolphin
has become a full file manager that leaves hardly any wishes open. The
dialogue that allows the running of command has received numerous
helpful features. Finally there is Kickoff that can replace the old
KMenu. However, KMenu is still available too.

</p>
All these changes taken by themselves would only justify a new release
3.6.x. The most important changes of KDE 4.0 are invisible for the
users. The KDE community made the decision to redesign a majority of the
base code. The beginning is the task of porting the base code to release
4 of the Qt toolkit release by Trolltech. This allows KDE 4 applications
to be used under numerous popular operating systems. In addition, the
libraries - known as kdelibs - have been streamlined.

</p>
Finally, several base technologies that will simplify the development of
KDE 4 applications have been integrated. Some of those technologies, as
Solid and Phonon will already be contained by the release 4.0. Others,
as Decibel and Akonadi will not be available until later releases. These
technologies are hidden for the users. Their full featureset will not be
seen until they are integrated into the applications running under KDE
4. This will step by step release the full potential of KDE 4.

</p>
[]{#Fundamentals}

</p>
[ Fundamentals]{.mw-headline}
-----------------------------

</p>
[]{#Platform_Independence}

</p>
### [ Platform Independence]{.mw-headline}

</p>
During the development of KDE 4, there has been a big emphasis on
platform independence. All KDE 4 application shall be able to run on all
popular operating systems (Windows, Mac OS X, etc.) and are currently
ported for this purpose. This is possible, among other things, due to
the high grade of flexibility of Qt. This is shown by the example of
Amarok 2. After only 2 days, it was possible to compile and start Amarok
2 on Windows. It is currently not planned to port Plasma, but the
developers made it known that they would not be surprised if "some nut"
would port Plasma onto Windows. During a proof of concept, it was shown
that Plasma could be compiled and started on a Neo 1973 Smartphone.

</p>
[]{#Qt_4}

</p>
### [ Qt 4]{.mw-headline}

</p>
The
[Qt-Toolkit](http://trolltech.com/products/qt/homepagects/qt/homepage "http://trolltech.com/products/qt/homepagects/qt/homepage"){.external
.text} by Trolltech is the foundation of KDE. With the new generation
Qt4 there have been several positive changes. One example is the
distribution of the library into finer granuality which alows to develop
smaller and more memory efficient programs. This also achieved that the
new KDE release uses far less memory than its predecessors. An important
part of Qt 4 is the new paint engine Arthur. It is able to use OpenGL
far more effective than it is used in Qt 3. In addition, a comprehensive
functionality for SVG was added.

</p>
KDE 4.0 is build on top of Qt 4.3. In addition, Qt 4.4 (final release 1
is scheduled for the first quarter of 2008) will be used, which is
already the foundation of Amarok 2.

</p>
[]{#Phonon}

</p>
### [ Phonon]{.mw-headline}

</p>
Phonon is contrary to some fears not a new sound system in the fashion
of GStreamer or similar, but rather as a layer between the sound system
and the audio applications. Phonon has not the the functionality to
allow komplex transformations of multimedia data, but serves as a simple
input and output layer for multimedia data to the backend (as i.e.
GStreamer, Xine, etc.). Important advantages for this are platform
independence and flexibility. In this way, KDE 4 applications do not
need to have any knowledge about the underlying multimedia architecture,
but only need to intereract with Phono's application interface.

</p>
It is not necessary to install an additional sound system on every
platform in order to allow KDE 4 applications to work. Applications can
simply access the functionality through the backend of the underlying
platform. Should the user decide to change the sound system during the
runtime of an application, it is only necessary for Photon to exchange
the backend without any interference of the running KDE 4 applications.
This means that problems as the one with a sleeping arts daemon will be
issues of the pasttime. aRts has been used in KDE 3 and before to play
and record sounds. The buffers filled up with time and after the wake-up
multiple sounds would be played in an overlaying fashion. Another
additional feature will be the possibility to have the sound output by
several applications be activitated dependent on each other. As an
example, the sounds of all other applications could be temporarily muted
while the user is listening to a webstream.

</p>
Trolltech has already announced that Phonon will be integrated into the
next Qt releases.

</p>
### [](http://wiki.kubuntu-de.org/Bild:KDE4-Systemeinstellungen.png "Bild:KDE4-Systemeinstellungen.png"){.image}

</p>
### [![Bild:KDE4-Systemeinstellungen.png](http://wiki.kubuntu-de.org/images/KDE4-Systemeinstellungen.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Systemeinstellungen.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Solid.png](http://wiki.kubuntu-de.org/images/KDE4-Solid.png){width="160" height="100"}](http://wiki.kubuntu-de.org/images/KDE4-Solid.png)[![Bild:KDE4-Phonon.png](http://wiki.kubuntu-de.org/images/KDE4-Phonon.png){width="160" height="100"}](http://wiki.kubuntu-de.org/images/KDE4-Phonon.png) {#bildkde4-systemeinstellungen.pngbildkde4-solid.pngbildkde4-phonon.png align="center"}

</p>
###  

</p>
[]{#Solid}

</p>
### [ Solid]{.mw-headline}

</p>
[Solid](http://solid.kde.org/ "http://solid.kde.org/"){.external .text}
is similar to Phonon a framework that allows KDE 4 application the
access or usage of hardware. In this context, there is a network manager
backend that allows applications to know at any time the status of the
network connections. If a WLAN hotspot is left, this allows any
applications that depend on an Internet connection to switch into an
offline mode. Due to the fact that Solid is quite new, this technology
must first be implemented into the applications. Further backends
currently available under Solid are backends for the battery management
and bluetooth.

</p>
[]{#Strigi}

</p>
### [ Strigi]{.mw-headline}

</p>
Strigi is the small and very fast index based desktop search engine that
is already known from Gutsy Gibbon. In contrast to the KDE 3 version,
Strigi is now far more mature and in conjunction with the semantic
functions provided by Nepomuk a very powerful search tool. Similar as to
the usage of beagle under Gnome, it is now possible to index files in
order to allow faster searches. In addition, Strigi works very resource
efficient and therefore does not put such a high load on the system as
other desktop search engines do.

</p>
[]{#Nepomuk}

</p>
### [ Nepomuk]{.mw-headline}

</p>
[Nepomuk](http://nepomuk-kde.semanticdesktop.org/xwiki/bin/view/Main/WebHome "http://nepomuk-kde.semanticdesktop.org/xwiki/bin/view/Main/WebHome"){.external
.text} is not a pure KDE project, but a big research and development
project which is supported by numerous companies, researchers and
developers. Their goal is the vision to revolutionise information
management with the aid of information technology by creating a semantic
desktop.

</p>
The implementation of Nepomuk in KDE 4 allows to tag files with keywords
(so called tags) or to add comments. In turn these tags can be used for
searching in a similar way as this is already possible on blogs or
multimedia sites such as Youtube. Since the tags remain associated to
the files even if they are renamed, it is very easy to search for files
that have been accidentally renamed. The tag system also allows files to
be sorted according to contents. As an example, a tag with the
description "dog" could be created which could be assigned to all video
files or image files that contain a dog. Nepomuk is already integrated
into Dolphin.

</p>
[]{#The_Most_Obvious_Changes_to_KDE_3.5.x}

</p>
[ The Most Obvious Changes to KDE 3.5.x]{.mw-headline}
------------------------------------------------------

</p>
[]{#Plasma}

</p>
### [ Plasma]{.mw-headline}

</p>
Certainly, the most obvious change in KDE 4 is Plasma, the new desktop.
It is fully based on the concept of widgets. Behind the widgets are
small applications that smong other things show the status of batteries,
rss feeds, or show a clock on the desktop. These widgets can be freely
placed either on the desktop, or on the taskbar. Previously two
different widgets were necessary for this.

</p>
Due to the fact that the widget recognises where it is placed, it
automatically adjusts its size and behaviour. As an example, a widget
which would show lots of information and maybe even a graphic on the
desktop, would show fewer but important information inside the taskbar.
Since these application are fully based on SVG technology, it is
possible to freely scale and rotate them.

</p>
The taskbar itself is now also a widget which allows the integration of
additional widget inside itself. This means the task panel, system tray
and K-button are also widgets that can placed and exchanged in the way
the user wishes. This allows more flexibility in creating the completely
individual desktop.

</p>
Since Plasma was one of the last projects that have been tackled during
the KDE 4 development, at this time, only a small set of widgets are
available. The panel can also configured in limited ways at this time.

</p>
<div align="center">

[![Bild:KDE4-Dophin-gruppiert.png](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-gruppiert.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-gruppiert.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Dolphin-Spalten.png](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-Spalten.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Dolphin-Spalten.png "Bild:KDE4-Dolphin-Spalten.png"){.image}[![Bild:KDE4-Dolphin-Symbole.png](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-Symbole.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Dolphin-Symbole.png "Bild:KDE4-Dolphin-Symbole.png"){.image}

</div>

</p>
[]{#Systemsettings}

</p>
### [ Systemsettings]{.mw-headline}

</p>
Kcontrol has been responsible for the configuration of KDE for a long
time. Due to all its options and its structure, it was too complex for
the taste of many users. Therefore, Kubuntu introduced Systemsettings,
which in turn has found its way into KDE 4 and replaces KControl. The
simplicity of its concept makes it easy for new users to configure the
environment according to their wishes. However, it still allows the
advanced users to configure the complex options of configuration of the
desktop.

</p>
[]{#Dolphin}

</p>
### [ Dolphin]{.mw-headline}

</p>
The file manager Dolphin was completely redesigned for KDE 4. In
addition to the features of Nepomuk, Dolphin offers a different model
that allows files to be sorted according different attributes in order
to manage them (i.e. alphabetically, user permissions, etc.). The tree
structure that is used by many users in the KDE 3 Version of Dolphin is
still available. In addition, Dolphin now allows a column display
similar to the one that is known from OS X. Dolphins main focus is the
management of files, which can easily be achieved with its comprehensive
functionality. However, it will also in future be possible to use
Konqueror for managing files.

</p>
[]{#Oxygen}

</p>
### [ Oxygen]{.mw-headline}

</p>
The new face of KDE has the name
[Oxygen](http://www.oxygen-icons.org/ "http://www.oxygen-icons.org/"){.external
.text}. It not only contains the new look & feel for the windows but
also a comprehensive set of icons which have been adjusted according to
the naming conventions of
[freedesktop.org](http://www.freedesktop.org/ "http://www.freedesktop.org"){.external
.text}. The named aim has been to design the icons in a uniform and
consistent way. The technology used is the vector format SVG. This
allows full scalability and dynamical adjustments to colour. The design
is completed with a KDE style and matching cursor theme and new sounds.

</p>
[]{#KWin}

</p>
### [ KWin]{.mw-headline}

</p>
Since the introduction of AIGLX it is possible for XServer to display
graphical effects similar to Mac OS X. In order to create such effects
it is necessary to have a composite manager as i.e. Compiz-Fusion.
Compositing does not only look very nice, but can also enhance the
usability. Therefore, KWin has been enhanced with its own composite
manager, which can be activated according to need and hardware
availability. The manager allows to switch on and off the different
effects that are available.

</p>
[]{#KRunner}

</p>
### [ KRunner]{.mw-headline}

</p>
As a substituion of the previous menu item "Run Command", which was able
to execute commands, KRunner has now been integrated. KRunner has been
extended and integrates now Katapult, Strigi, and the command line
interface as one. After the input of a term, all sources will be
searched simultaneously and depending on the result, different options
will be offered for selection.

</p>
<div align="center">

[![Bild:KDE4-Krunner.png](http://wiki.kubuntu-de.org/images/KDE4-Krunner.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Krunner.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Okular.png](http://wiki.kubuntu-de.org/images/KDE4-Okular.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Okular.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Kwin.png](http://wiki.kubuntu-de.org/images/KDE4-Kwin.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Kwin.png "Bild:KDE4-Systemeinstellungen.png"){.image}

</div>

</p>
[]{#Prospects_of_KDE_4.x}

</p>
[ Prospects of KDE 4.x]{.mw-headline}
-------------------------------------

</p>
According to the paradigm of the open source community "release often,
release early", some of the core technologies for the KDE desktop will
not be available in the first release of KDE 4. In particular, this can
be said about Akonadi, which is the individual private information
management for KDE. Akonadi shall give a central repository for all
kinds of groupware data, which in turn will be made available for all
applications. The uniformity and access control for the data will
prevent that applications can interfere with each other or the need of
data conversions.

</p>
It can be expected that the already existing technologies will be
integrated into the applications and step by step all KDE applications
will be ported to Qt4 and KDE 4. This also relates to some important
applications like Amarok and KOffice. The new version 2.0 of KOffice
could not be released in time for KDE 4.0. However, there is great hope
for it. In particular, it is an aim to make KOffice2 the default office
suite for Kubuntu.

</p>
High expectation also exist for the audio player Amarok 2. There will be
a completely redesigned user interface which will be built around the
context browser. It will have integrations, among others, for the
popular online services as well as context information from wikipedia
and a built-in of the Magnatune shops.

</p>

