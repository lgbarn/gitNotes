# Reference List

<a name="top"></a>

## TOC

1.  [Related to Scripting & Computer Languages](#scripting-and-languages)
    1.  [Atom](#atom)
    2.  [Markdown](#markdown)

## Related to Mac OS Support & Administration

-   [HP Printer Driver FTP](ftp://ftp.hp.com/pub/softlib/software12/HP_Quick_Start/osx/Installations/Essentials//)
-   [Connet to a Wireless Network from CLI](http://osxdaily.com/2011/04/12/connect-wireless-network-command-line/)

\[[top](#top)]

### App Stuff ...

-   [NoMAD](https://nomad.menu/downloads/ "No More Active Directory")

-   [Backblaze](https://www.backblaze.com "Data backup solution")

-   [DeployStudio](https://deploystudio.wikispaces.com "DeployStudio Wiki")

\[[top](#top)]

### Documentation

-   **Apple**

    -   APFS [Apple Developer - APFS](https://developer.apple.com/library/content/documentation/FileManagement/Conceptual/APFS_Guide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40016999-CH1-DontLinkElementID_19)
    -   [macOS Builds](https://support.apple.com/en-us/HT201260)
    -   [Apple Video Adapters and Cables](https://support.apple.com/en-us/HT201853 "About Apple Video Adapters and Cables")
    -   [Mac Startup Cmd Options](https://support.apple.com/en-us/HT201255)
    -   [Apple software Restore (ASR)](https://en.wikipedia.org/wiki/Apple_Software_Restore)

-   [IBM SPSS Documentation](ftp://public.dhe.ibm.com/software/analytics/spss/documentation/statistics/24.0/en/client/InstallationDocuments/MacOS/ "Documentation for IBM SPSS")

-   **Apple & AirWatch**

    -   [My
    AirWatch](https://my.air-watch.com/help/9.1/en/Content/Platform_Guides/macOS/C/Profiles_Overview.htm?TocPath=PROFILES|macOS%C2%A0Device%20Profiles|_____0)

-   [Jamf](jamf.com "jamf Mac administration")

    -   [jampPro Admin Admin Guide](http://docs.jamf.com)  
    -   [jamf Developer](http://developer.jamf.com/index "jamf Developter portal")
    -   [jamf Marketplace](marketplac.jamf.com "jamf curated apps")
    -   [jamfPro v VMware
    AirWatch](https://www.itcentralstation.com/products/comparisons/jamf-pro_vs_vmware-airwatch)

\[[top](#top)]

## Unix & GNU/Linux

-   [Sane scanner](https://wiki.archlinux.org/index.php/SANE)

-   Linux Journey - <https://linuxjourney.com/lesson/etc-group-file>

-   netboot.xyz

-   Banking with a live cd: <http://krebsonsecurity.com/2012/07/banking-on-a-live-cd/>

-   SSH Tricks: <http://www.linuxjournal.com/article/6602>

-   Rsync command examples - <http://www.thegeekstuff.com/2010/09/rsync-command-examples/>

-   POSIX - <https://en.wikipedia.org/wiki/POSIX>

-   Security Enhanced Linux: <http://selinuxproject.org/page/Main_Page>

-   Cool old terminal - old looking terminal for linux: <http://linuxg.net/how-to-install-cool-old-term-0-9-on-ubuntu-14-04-debian-jessie>

\[[top](#top)]

## Related to Windows Administration

-   List of WMIC CSProduct Get Name Results - <http://faqshop.com/misc/list-of-wmic-csproduct-get-name-results/>

-   [Troubleshooting Slow Logons via PowerShell](https://www.citrix.com/blogs/2015/08/05/troubleshooting-slow-logons-via-powershell/)

-   [Logon GPO Analysis via PowerShell](https://www.controlup.com/blog/logon-gpo-analysis-via-powershell/)

\[[top](#top)]

### SCCM Administration

-   [SCCM Queries with PowerShell](http://blog.ctglobalservices.com/powershell/kaj/working-with-queries-in-configmgr-with-powershell/)

-   [WMI SCCM Queries](https://www.andersrodland.com/ultimate-sccm-querie-collection-list/)

-   Convert from BIOS to UEFI Using SCCM - <https://www.systemcenterdudes.com/sccm-bios-uefi-conversion-task-sequence>

    -   Another Article regarding Bios to UEFI conversion - <https://docs.microsoft.com/en-us/sccm/osd/deploy-use/task-sequence-steps-to-manage-bios-to-uefi-conversion>

-   Deploy Windows from Captured Media -  <https://blogs.technet.microsoft.com/configurationmgr/2010/04/12/how-to-set-up-a-task-sequence-to-deploy-windows-7-images-captured-via-an-sccm-2007-capture-cd/>

-   Driver management - <https://technet.microsoft.com/en-us/library/hh301101.aspx>

\[[top](#top)]

### Driver Resources

-   [ Microsoft Surface Drivers](https://docs.microsoft.com/en-us/surface/deploy-the-latest-firmware-and-drivers-for-surface-devices#a-href-idsurface-pro-3-asurface-pro-3)
-   HP Drivers - <http://www8.hp.com/us/en/ads/clientmanagement/overview.html#manageability-tools>

## VMare

### VMware AirWatch

-   [start here - AirWatch Leaning Path](https://mylearn.vmware.com/mgrReg/plan.cfm?plan=47955&ui=www_edu)

\[[top](#top)]
<a name="scripting-and-languages"></a>

## Related to Scripting & Computer Languages

### Vim Customization

-   [vim wiki](http://vim.wikia.com/wiki)
-   [NerdTree Doc](https://github.com/scrooloose/nerdtree/blob/master/doc/NERDTree.txt)

<a name="atom"></a>

### Atom Customization ...

```css
// Selection color - added by captam3rica
atom-text-editor::shadow .selection .region {
    background-color: #EA4760;
}

// To style other content in the text editor's shadow DOM, use the ::shadow expression
atom-text-editor::shadow .cursor {
  border-color: #EA4760;
}

// Minimap cursor color style
.minimap .cursor-line {
    background: #EA4760;
}
```

<a name="markdown"></a>

### Markdown

-   [CommmonMark](http://commonmark.org/)

    -   [CommmonMark Spec](http://spec.commonmark.org/)

-   [Brett Terpstra: Write Better Markdown](http://brettterpstra.com/2015/08/24/write-better-markdown/)

-   [vim wiki](http://vim.wikia.com/wiki)
-   [vim-markdownfmt](https://github.com/moorereason/vim-markdownfmt)

-   Table of contents

    ```md
    # Markdown syntax

      # Table of contents
      1. [Introduction](#introduction)
      2. [Some paragraph](#paragraph1)
      3. [Sub paragraph](#subparagraph1)
      4. [Another paragraph](#paragraph2)

      ## This is the introduction <a name="introduction"></a>
      Some introduction text, formatted in heading 2 style

      ## Some paragraph <a name="paragraph1"></a>
      The first paragraph text

      ### Sub paragraph <a name="subparagraph1"></a>
      This is a sub paragraph, formatted in heading 3 style

      <a name="paragraph2"></a>
      ## Another paragraph
      The second paragraph text
    ```

\[[top](#top)]

### Bash

-   [bashoneliners.com](http://www.bashoneliners.com/oneliners/oneliner/popular/)
-   Shell Variables - <https://www.gnu.org/software/bash/manual/bash.html#Shell-Variables>
-   User input with a while loop - <http://alvinalexander.com/linux-unix/shell-script-how-prompt-read-user-input-bash>
-   8 examples of Bash if statements - <http://bencane.com/2014/01/27/8-examples-of-bash-if-statements-to-get-you-started/>
-   07.18.2017 - [25 Simple Find commands](http://www.binarytides.com/linux-find-command-examples/)
-   07.15.2017 - [The /sbin Directory](http://www.linfo.org/sbin.html)
-   **08.01.2016** - [Working with tar](http://www.tecmint.com/18-tar-command-examples-in-linux/)

\[[top](#top)]

### RegEx

-   [RegEx - Grymoire](http://www.grymoire.com/Unix/Regular.html "Learn about regex")

\[[top](#top)]

### PowerShell

-   [Memory and Handle Quotas in the WMI Provider Ser](https://blogs.technet.microsoft.com/askperf/2008/09/16/memory-and-handle-quotas-in-the-wmi-provider-service/)
-   Bypass Execution Policies - <https://blog.netspi.com/15-ways-to-bypass-the-powershell-execution-policy/>

\[[top](#top)]

### Python

-   For **pycodestyle** - PEP8 linter for _Atom_
    -   `pip (or pip2) install pycodestyle && apm install pycodestyle`
-   Python for InfoSec: <http://strategicsec.com/python-for-infosec-pros-2015/>
-   Python Naming Conventions: <http://visualgit.readthedocs.io/en/latest/pages/naming_convention.html>

\[[top](#top)]

### sed

-   [Learn Sed](http://www.grymoire.com/Unix/Sed.html)

## Software

-   Borg Backup - (<http://borgbackup.readthedocs.io/en/stable/>)
-   Sync Thing
-   unRAID - <http://lime-technology.com/>
-   Done - OverLeaf - <https://www.overleaf.com/> - online text editor
-   Done - KeePass - <http://keepass.info/download.html> - OS password locker
-   Synology NAS - <http://www.synology.com/en-us/products/compare_products/DS214+/DS412+>
-   Qnap NAS servers - <http://www.staples.com/office/supplies/StaplesProductDisplay?storeId=10001&catalogIdentifier=2&partNumber=IM1PK7895&langid=-1&cid=PS:GooglePLAs:IM1PK7895&srccode=cii_17588969&cpncode=35-172700112-2>

### Web Browser Settings

-   Chrome, Chromium, and Vivaldi Autofill Settings: `chrome://settings/search#autofill`
-   Opera flag settings: `opera://flags/`

    -   Smooth Scrolling: Disabled
    -   Experimental QUIC (Similar to TCP but over UDP): Enabled
## Certifications

-   GIAC Certified Incident Handler - <http://www.giac.org/certification/certified-incident-handler-gcih>
-   GIAC Certified Forensic Examiner - <http://www.giac.org/certification/certified-forensic-examiner-gcfe>
-   Apple Certified Macintosh Technician
-   macOS Certified Technician 
-   Certified Security Analyst 
-   Security Plus ce
-   Linux Foundation Certified System Administrator 
-   Red Hat Certified System Administrator

## Security Tools & Info ...

-   Anonymous Web browsing - <http://lifehacker.com/150074/anonymous-web-browsing-20>
-   WikiLeaks DarkMatter -  <https://wikileaks.org/vault7/darkmatter/document/SonicScrewdriver_1p0/page-3/#pagination>
-   Pentesterlab.com - <http://pentesterlab.com/exercises/>
-   Rescator[dot]cc - underground black market where stolen cc were first seen to
    be for sale
-   Synolocker: <http://www.f-secure.com/weblog/archives/00002733.html>
-   Netflix and Security Monkey - <http://techblog.netflix.com/2014/06/announcing-security-monkey-aws-security.html>
-   Critical Security Controls: <http://www.sans.org/critical-security-controls/>
-   NIST Cyber Security Framework - <http://www.nist.gov/cyberframework/upload/cybersecurity-framework-021214-final.pdf>
-   Using Google to DDoS any Website - <http://chr13.com/2014/03/10/using-google-to-ddos-any-website/>
-   2014.05.27 - Using Facebook to DDoS any Website - <http://chr13.com/2014/04/20/using-facebook-notes-to-ddos-any-website/>
-   Fishing for hackers Analysis of a Linux server attack - <http://draios.com/fishing-for-hackers/>
-   2014.04.24 - Show passwords hidden by asterisks or stars - <http://www.tweakandtrick.com/2011/04/asterisk-password-star-show-view-reveal.html>
-   2014.04.24 - Cloud fogger - <http://thehackernews.com/2014/01/how-to-encrypt-your-files-before.html>
-   2014.03.11 - Password Protecting the BIOS - <http://security.blogoverflow.com/2014/02/qotw-50-does-password-protecting-the-bios-help-in-securing-sensitive-data/>

\[[top](#top)]

### Security Tools

#### ClamAV

-   sudo freshclam: update the av databases
-   sudo clamscan --recursion --infected --bell --suppress-ok-results --log=[your-file.log] / :

    -   scan the entire system
    -   Scan through directories as well as subdirectories  
    -   Sound a bell upon virus detection
    -   Only show infected files.
    -   Suppress the output of files with the "OK" status
    -   log the output to a file

Other useful flags ...

    -   --cross-fs-[yes/no]: tell clam to traverse other file systems
    -   --file-list=[file]: scan the listed files line by line
    -   --move=[DIRECTORY]: move files into the specified directory
    -   --detect-structured=[yes/no]: Use the **DLP** module to SSN and CC inside of docs and txt files.
    -   --scan-mail=[yes/no]: if turned off, the file will still be scanned, but will not parse messages and attachments.
    -   --scan-pdf=[yes/no]: scan within PDF docs. If turned off, decoding and extra processing will not happen
    -   --scan-html=[yes/no]
    -   --scan-xmldocs=[yes/no]

Supports data streaming

    -   `cat textfile.txt | clamscan -`

* * *

-   07.13.2017 - AngryIP - (<https://github.com/angryip/ipscan>
-   OpenVAS: <http://www.openvas.org/>
-   Fail2ban Documentation: <http://www.fail2ban.org/wiki/index.php/MANUAL_0_8>
-   2014.08.08- Vulnhub.com - vulnerable virtual machines
-   <http://www.openbl.org/>
-   How to generate OpenSSL keys - <http://openssl.6102.n7.nabble.com/Machine-certificate-td906.html>
-   Blowfish particulars - <https://www.schneier.com/paper-blowfish-fse.html>
-   Hack this Site - <https://www.hackthissite.org/>
-   John the Ripper Password Cracker
-   OWASP - <https://www.owasp.org/index.php/Main_Page>
-   Lynis Enterprise Suite: vulnerability scanner for arch linux (Rootkit.nl)
-   -   deft: digital forensics for Linux (deftlinux.net)
-   **Done** - Arch Assault: security software (Because of rolling release)
-   ssl stripper - pulls the ssl cert off and runs the site through http so that
    they can read the content.
-   Tortilla, whonix, **Done** - tails

    -   <https://github.com/CrowdStrike/Tortilla>
    -   <http://distrowatch.com/table.php?distribution=Tails>
    -   <https://www.whonix.org/wiki/Download>

-   mimicats
-   OSSIM, OSSEC - created by alien vault. h
-   IDS: AIDE, OSSEC, Snort
-   Metasploit, Set, Dsploit, Etercap
-   wifighter, evil ip, reverse shell
-   Rever and Patty brute forcers, AirCrack
-   iperf - wireless trouble shooting
-   Hack this Site - <https://www.hackthissite.org/>
-   RAM Scraper
-   Power Top

\[[top](#top)]

### Encryption & Cryptography

-   [Hashing vs Encryption](http://www.darkreading.com/safely-storing-user-passwords-hashing-vs-encrypting/a/d-id/1269374)

\[[top](#top)]

## Networking

-   [IPv6 Crash Course](https://www.linux.com/learn/ipv6-crash-course-linux)
-   [OpenWRT](<http://wiki.openwrt.org/toh/netgear/wnr1000 - OS router firmware>)
-   [Packet Life](http://packetlife.net/)
