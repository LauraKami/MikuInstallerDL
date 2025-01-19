# MikuInstallerDL
To easily install MikuMikuDance and PMXEdidor with all dependencies and tools.

Video : https://youtu.be/Q5Fkyhu3Ey0

The zip file to download : [SetupMikuInstaller.v1.0.2.zip](https://github.com/LauraKami/MikuInstallerDL/releases/download/v1.0.2/SetupMikuInstaller.v1.0.2.zip)

[French version of this page, and download from france ](https://mikumikudance.fr/miku_installer)

Miku_Installer works on Windows 10 and 11, 64-bit version. It installs dependencies and tools to use MikuMikuDance and PMX Editor.

You need 3 GB of free space for the software, and plan 50 GB to create animations and videos.

The software is downloaded to your PC, it comes from Microsoft, Bandizip, GitHub and Japanese sites for MikuMikuDance, MMEffect and PMX Editor.

Mostly, the downloads are automatic, but for some, you will have to help Miku download files…

If your PC is new, the installation is a bit long, because there are a lot of Microsoft software to install, and these are the most painful…

So, Miku Installer will offer you animation extracts and will make you discover magnificent MMDs.

![ecran1](https://github.com/user-attachments/assets/037aace2-8648-4737-b806-f49f80420d64)


# Main version
 - Miku Installer version bêta v004 du 5 janvier 2023
 - MikuInstaller on GitHub 1.0.1 15 Junary 2025

# Tips

Some details to properly install MikuMikuDance.

- Your Windows must be up to date. If there is a pending Windows Update, it will block. At the moment, there are a lot of updates, so make sure it is done.
- If it loops on a download, (for example Bandizip), close Miku_Installer, let it rest for 5 minutes and restart the application.
- If it blocks (more than 5 minutes and nothing progresses) close Miku_Installer, do the updates, restart your PC and restart Miku_Installer.
- Your PC can be a tower (like a Gaming PC) or a basic office laptop.
- You need a PC with 4 GB of memory, 8 GB is better, a basic processor can be suitable i3,I5,i7 (or AMD equivalent), I use a Pentium (R) Silver N5030 CPU @ 1.10GHz, it is not a arrow, but it does not make noise.
- You need a basic graphics card (the one integrated into the processor works very well), obviously if you have a Gamer graphics card it will work even faster for rendering movies and converting videos.
- Windows 10 works very well, it is useless, or even not recommended to update to Windows 11. It does not bring any benefit, except that the machine will lag...
- The best is to have a 3-button mouse, but you can work with a laptop pad.
- If you are planning to buy a PC to get into 3D, get a machine with an Nvidia graphics card, I know, I will make AMD angry, but it is likely that after MikuMikuDance, you will learn other software like Blender, Maya, C4D. And Blender only works on Nvidia cards, otherwise you have to get high-end AMD. So I have an AMD card for sale... ;o)

# MikuInstaller icon
![MikuInstaller icon](https://github.com/LauraKami/MikuInstallerDL/blob/main/image/IconMikuInstaller.png)
- Pose & artistic choice: @Yhozai [https://www.instagram.com/yhozai/](https://www.instagram.com/yhozai/)
- Image rendered by MikuMikuDance (c)Yu Higochi [MikuInstaller](https://mikumikudance.fr/miku_installer/)
- 3D Model: created by MMD stylist 0N3B33S, TDA base [MMD - MODEL PACK DL SOBeR - SUZY on DevianArt](https://www.deviantart.com/0n3b33s/art/MMD-MODEL-PACK-DL-SOBeR-SUZY-931230081)
- Icon converted by [Greenfish Icon Editor Pro 4.2](http://greenfishsoftware.org/) (RIP? freeware)

# What will be installed on your PC

Miku_Installer searches for software on your PC, if it is already present it does not install the software.

All Microsoft software comes from Microsoft and not from obscure zip or drive.

Other software comes from GitHub or the official website of their publisher.

Softwares are free for individual use (for companies, you have to study each license).

- Microsoft Visual C++RunTime 2008 64 bits
- Microsoft Visual C++ RunTime 2010 64 bits
- Microsoft Visual C++ RunTime 2012 64 bits
- Microsoft Dot Net Desktop 6 and 8
- (v1.0.2 is no longer installed) Microsoft Dot Net 3.5 (includes 2.0 and 2.5)
- Microsoft Direct X version 9 (old version for Miku, Windows 10/11 contains version 12).<br>
(these last two are long to install, you can watch a full-length MMD movie).
- WGET from the Free Software Foundation, a fast and efficient dowloader.
- Bandizip (c) Bandisoft, an unzipper from the country of K-POP, friend of Asian characters, especially Japanese. (can replace Winzip, WinRar and 7zip).
- UtVideo (Video codec) © UMEZAWA Takeshi. The only codec without viruses and without trojans, Open Source (GitHub edition).
- Notepad++ (editor compatible with Asian characters) © Don Ho (go see his CV to understand why it manages Asian characters so well).
- FFmpeg (Video converter) Tm Fabrice Belard (a Frenchman, creator of tcc for connoisseurs…) (FFmpeg will be used by MikuVideo)
- (v1.0.2) MikuVideo A tool to inspect and convert video from an to MikuMikuDance by me
- (v1.0.2) YtDlp, YtDlpGui, Aria2 : tools for teenagers to studies videos from internet ...

## Then Miku_Installer will look for software in Japan on their official sites:

- MMD: MikuMikuDance v962 English by Yu Higochi.
- MME: MikuMikuEffect v037 by BuryokuKainyuu-P
- (Updated) PmxEditor_0254f_EN-2.0 by KyokuhokuP, translated by Innochi-PM
- (v1.0.2) PmxEditor_0273_1.0.0 by KyokuhokuP, translated by Inochi-PM and johnwithlenon

MikuInstaller unzips everything, organizes the software, and puts it all in C:\MMD (MikuMikuDance is not a "standard" software, you should not install it in ProgramFiles).

It creates shortcuts with beautiful icons on the desktop, in the 'Start' menu and in 'My Documents'. It's up to you to drag them into the taskbar.

Afterwards, you just have to open MikuMikuDance and do File > Open > choose the demo file "Sample.pmm" and click on the [Play] button.

Afterwards, you have my tutorials on MikuMikuDance.fr ... and many others on YouTube in English, Spanish and many other languages.

I programmed Miku_Installer in C# with Visual Studio 2022 and .Net 6.0. The first versions that you won't see, were in: CMD Shell, PowerShell, Python text, InnoSetup (pascal), Python pySimpleGui, Python Kivy. All these versions took me several months.
