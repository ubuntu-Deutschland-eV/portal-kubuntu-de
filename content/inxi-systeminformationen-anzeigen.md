Title: inxi - Systeminformationen anzeigen
Date: 2014-03-30 16:07
Author: Monika Eggers
Tags: Kubuntu
Slug: inxi-systeminformationen-anzeigen

inxi ist ein Kommandozeilenprogramm, das Systeminformationen schön
formatiert und farbig anzeigt.

Installiere es mit `sudo apt-get install inxi`

Führe es aus mit `inxi -Fxxxplu`

Beispielausgabe (die Farbe kann hier nicht gezeigt werden):

	System:    Host: lilly Kernel: 3.11.0-18-generic x86_64 (64 bit, gcc: 4.8.1) 
		   Desktop: KDE 4.11.5 (Qt 4.8.4) info: plasma-desktop dm: lightdm Distro: Ubuntu 13.10
	Machine:   Mobo: ASUSTeK model: M5A78L-M/USB3 version: Rev X.0x Bios: American Megatrends version: 0801 date: 11/30/2011
	CPU:       Quad core AMD FX-4100 (-MCP-) cache: 8192 KB flags: (lm nx sse sse2 sse3 sse4_1 sse4_2 sse4a ssse3 svm) bmips: 28930.3 
		   Clock Speeds: 1: 3600.00 MHz 2: 3600.00 MHz 3: 3600.00 MHz 4: 3600.00 MHz
	Graphics:  Card: NVIDIA G98 [GeForce 9300 GS] bus-ID: 01:00.0 chip-ID: 10de:06e1 
		   X.Org: 1.14.5 driver: nvidia Resolution: 1440x900@60.0hz, 1440x900@60.0hz 
		   GLX Renderer: GeForce 9300 GS/PCIe/SSE2 GLX Version: 3.3.0 NVIDIA 304.108 Direct Rendering: Yes
	Audio:     Card: Advanced Micro Devices [AMD/ATI] SBx00 Azalia (Intel HDA) 
		   driver: snd_hda_intel bus-ID: 00:14.2 chip-ID: 1002:4383 
		   Sound: Advanced Linux Sound Architecture ver: k3.11.0-18-generic
	Network:   Card: Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller 
		   driver: r8169 ver: 2.3LK-NAPI port: e800 bus-ID: 03:00.0 chip-ID: 10ec:8168
		   IF: eth0 state: up speed: 100 Mbps duplex: full mac: c8:60:00:57:dc:d6
	Drives:    HDD Total Size: 500.1GB (36.1% used)
		   1: id: /dev/sda model: WDC_WD5000AADS size: 500.1GB serial: WD-WCAV96879403 
	Partition: ID: / size: 19G used: 10G (58%) fs: ext4 dev: /dev/sda5 
		   label: N/A uuid: 87b34b2e-2446-41ad-beaf-729a39eb8132
		   ID: /home size: 437G used: 159G (39%) fs: ext4 dev: /dev/sda7 
		   label: N/A uuid: f7b838e3-380f-4af2-8616-3cbd3cc31cc7
		   ID: swap-1 size: 4.00GB used: 0.00GB (0%) fs: swap dev: /dev/sda6 
		   label: N/A uuid: 52add819-d491-4a92-af9c-e624faa6eaaf
	RAID:      System: supported: N/A
		   No RAID devices detected - /proc/mdstat and md_mod kernel raid module present
		   Unused Devices: none
	Sensors:   System Temperatures: cpu: 67.0C mobo: 42.0C gpu: 0.0:76C 
		   Fan Speeds (in rpm): cpu: 2860 sys-1: 0 
	Info:      Processes: 203 Uptime: 5:43 Memory: 2531.1/7968.1MB Runlevel: 2 Gcc sys: 4.8.1 alt: 4.6/4.7 
		   Client: Shell (bash 4.2.45 running in konsole) inxi: 1.9.12 
