## HowTo

DISM /online /Get-TargetEditions
DISM /online /Set-Edition:ServerStandard /ProductKey:xxxxx-xxxxx-xxxxx-xxxxx-xxxxx /AcceptEula
(reboot)

slmgr /ipk ххххх- ххххх – ххххх – ххххх – ххххх

slmgr /skms [serverhere]:1688

slmgr /ato


Test if a KMS server is online or not
-------

http://technet.microsoft.com/en-us/library/ff793433.aspx


```bash
/skms Name[:Port] | : port [Activation ID] [Activation ID] 
slmgr.vbs /skms KMSServer2
slmgr.vbs /ato
```

Example:
`nslookup -type=srv _vlmcs._tcp.kms.digiboy.ir`



Online KMS host address:
--------
* kms.srv.crsoo.com
* cy2617.jios.org
* kms.digiboy.ir
* kms.cangshui.net
* kms.library.hk
* hq1.chinancce.com
* kms.loli.beer
* kms.v0v.bid
* 54.223.212.31
* kms.jm33.me
* nb.shenqw.win
* kms.izetn.cn
* kms.cin.ink
* 222.184.9.98
* kms.ijio.net
* fourdeltaone.net:1688
* kms.iaini.net
* kms.cnlic.com
* kms.51it.wang
* key.17108.com
* kms.chinancce.com
* kms.ddns.net
* windows.kms.app
* kms.ddz.red
* franklv.ddns.net
* kms.mogeko.me
* k.zpale.com
* amrice.top
* m.zpale.com
* mvg.zpale.com
* kms.shuax.com
* kensol263.imwork.net:1688
* xykz.f3322.org
* kms789.com
* dimanyakms.sytes.net:1688
* kms8.MSGuides.com
* kms.03k.org:1688
* kms.ymgblog.com
* kms.bige0.com
* kms9.MSGuides.com
* kms.cz9.cn
* kms.lolico.moe
* kms.ddddg.cn
* kms.zhuxiaole.org
* kms.moeclub.org
* kms.lotro.cc
* zh.us.to
* noair.strangled.net:1688

Keys:
Home/Core                            TX9XD-98N7V-6WMQ6-BX7FG-H8Q99        
Home/Core (Country Specific)         PVMJN-6DFY6-9CCP6-7BKTT-D3WVR  
Home/Core (Single Language)          7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH  
Home/Core N                          3KHY7-WNT83-DGQKR-F7HPR-844BM 
Professional                         W269N-WFGWX-YVC9B-4J6C9-T83GX 
Professional N                       MH37W-N47XK-V7XM9-C7227-GCQG9
Professional Enterprise				 
Professional Workstation			 
Enterprise                           NPPR9-FWDCX-D2C8J-H872K-2YT43 
Enterprise N                         DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 
Education                            NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 
Education N                          2WH4N-8QGBV-H22JP-CT43Q-MDWWJ 
Enterprise 2015 LTSB                 WNMTR-4C88C-JK8YV-HQ7T2-76DF9
Enterprise 2015 LTSB N               2F77B-TNFGY-69QQF-B8YKP-D69TJ 
Enterprise 2016 LTSB                 DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ  
Enterprise 2016 LTSB N               QFFDN-GRT3P-VKWWX-X7T3R-8B639


  
Windows 10 Enterprise N Eval Activation Key 	MNXKQ-WY2CT-JWBJ2-T68TQ-YBH2V
Windows 10 Enterprise S Eval Activation Key 	7TNX7-H36JG-QFF42-K4JYV-YY482
Windows 10 Enterprise S N Eval Activation Key 	D3M8K-4YN49-89KYG-4F3DR-TVJW3
Windows 10 Enterprise Eval Activation Key 	VPMWD-PVNRR-79WJ9-VVJQC-3YH2G
Windows 10 Starter Activation Key 	D6RD9-D4N8T-RT9QX-YW6YT-FCWWJ
Windows 10 Education N Activation Key 	84NGF-MHBT6-FXBX8-QWJK7-DRR8H
Windows 10 Education Activation Key 	YNMGQ-8RYV3-4PGQ3-C8XTP-7CFBY
Windows 10 Professional Activation Key 	VK7JG-NPHTM-C97JM-9MPGT-3V66T
Windows 10 Professional N Activation Key 	2B87N-8KFHP-DKV6R-Y2C8J-PKCKT
Windows 10 Core Activation Key 	YTMG3-N6DKC-DKB77-7M9GH-8HVX7
Windows 10 Core N Activation Key 	4CPRK-NM3K3-X6XXQ-RXX86-WXCHW
Core Single Language 	BT79Q-G7N6G-PGBYW-4YWX6-6F4BT
Core Country Specific 	N2434-X9D7W-8PF6X-8DV9T-8TYMD


Windows 10 Home – YTMG3-N6DKC-DKB77-7M9GH-8HVX7
Windows 10 Home N – 4CPRK-NM3K3-X6XXQ-RXX86-WXCHW
Windows 10 Pro – VK7JG-NPHTM-C97JM-9MPGT-3V66T
Windows 10 Pro N – 2B87N-8KFHP-DKV6R-Y2C8J-PKCKT
Windows 10 Pro for Workstations – DXG7C-N36C4-C4HTG-X4T3X-2YV77
Windows 10 Pro N for Workstations – WYPNQ-8C467-V2W6J-TX4WX-WT2RQ
Windows 10 S – 3NF4D-GF9GY-63VKH-QRC3V-7QW8P
Windows 10 Education – YNMGQ-8RYV3-4PGQ3-C8XTP-7CFBY
Windows 10 Education N – 84NGF-MHBT6-FXBX8-QWJK7-DRR8H
Windows 10 Pro Education – 8PTT6-RNW4C-6V7J2-C2D3X-MHBPB
Windows 10 Pro Education N – GJTYN-HDMQY-FRR76-HVGC7-QPF8P
Windows 10 Enterprise – XGVPP-NMH47-7TTHJ-W3FW7-8HV2C
Windows 10 Enterprise S – NK96Y-D9CD8-W44CQ-R8YTK-DYJWX
Windows 10 Enterprise N – WGGHN-J84D6-QYCPR-T7PJ7-X766F
Windows 10 Enterprise G N – FW7NV-4T673-HF4VX-9X4MM-B4H4T
Windows 10 Enterprise N LTSB 2016: RW7WN-FMT44-KRGBK-G44WK-QV7YK
