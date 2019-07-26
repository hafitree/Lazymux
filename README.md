# # lazymux.py - Lazymux v3.0
# - * - การเข้ารหัส: utf-8 - * -
# #
นำเข้าระบบปฏิบัติการ
sys นำเข้า
จากเวลานำเข้านอนเป็นหมดเวลา
จาก core.lzmcore นำเข้า *

def  main ():
	แบนเนอร์ ()
	พิมพ์ "    [01] การรวบรวมข้อมูล"
	พิมพ์ "    [02] Vulnerability Scanner "
	พิมพ์ "    [03] การทดสอบความเครียด"
	พิมพ์ "    [04] การโจมตีรหัสผ่าน"
	พิมพ์ "    [05] การแฮ็กเว็บ"
	พิมพ์ "    [06] เครื่องมือการเอารัดเอาเปรียบ"
	พิมพ์ "    [07] การดมกลิ่น & การปลอมแปลง"
	พิมพ์ "    [08] อื่น ๆ\ n "
	พิมพ์ "    [10] ออกจาก Lazymux \ n "
	lazymux =  raw_input ( " lzmx> " )

	if lazymux ==  " 1 " หรือ lazymux ==  " 01 " :
		พิมพ์ " \ n     [01] Nmap "
		พิมพ์ "     [02] เรดฮอว์ก"
		พิมพ์ "     [03] D-Tect "
		พิมพ์ "     [04] sqlmap "
		พิมพ์ "     [05] Infoga "
		พิมพ์ "     [06] ReconDog "
		พิมพ์ "     [07] AndroZenmap "
		พิมพ์ "     [08] sqlmate "
		พิมพ์ "     [09] AstraNmap "
		พิมพ์ "     [10] WTF "
		พิมพ์ "     [11] Easymap "
		พิมพ์ "     [12] BlackBox "
		พิมพ์ "     [13] XD3v "
		พิมพ์ "     [14] Crips "
		พิมพ์ "     [15] SIR "
		พิมพ์ "     [16] EvilURL "
		พิมพ์ "     [17] กองหน้า"
		พิมพ์ "     [18] Xshell "
		พิมพ์ "     [19] OWScan "
		พิมพ์ "     [20] OSIF "
		พิมพ์ "     [21] Devploit "
		พิมพ์ "     [22] Namechk "
		พิมพ์ "     [23] AUXILE "
		พิมพ์ "     [24] inther "
		พิมพ์ "     [25] GINF "
		พิมพ์ "     [26] การติดตาม GPS "
		พิมพ์ "     [27] ASU "
		พิมพ์ "     [28] fim \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		infogathering =  raw_input ( " lzmx> " )
		
		if infogathering ==  " 01 " หรือ infogathering ==  " 1 " :
			nmap ()
		elif infogathering ==  " 02 " หรือ infogathering ==  " 2 " :
			เหยี่ยวแดง()
		elif infogathering ==  " 03 " หรือ infogathering ==  " 3 " :
			dtect ()
		elif infogathering ==  " 04 " หรือ infogathering ==  " 4 " :
			sqlmap ()
		elif infogathering ==  " 05 " หรือ infogathering ==  " 5 " :
			infoga ()
		elif infogathering ==  " 06 " หรือ infogathering ==  " 6 " :
			reconDog ()
		elif infogathering ==  " 07 " หรือ infogathering ==  " 7 " :
			androZenmap ()
		elif infogathering ==  " 08 " หรือ infogathering ==  " 8 " :
			sqlmate ()
		elif infogathering ==  " 09 " หรือ infogathering ==  " 9 " :
			astraNmap ()
		elif infogathering ==  " 10 " :
			WTF ()
		elif infogathering ==  " 11 " :
			easyMap ()
		elif infogathering ==  " 12 " :
			กล่องดำ()
		elif infogathering ==  " 13 " :
			xd3v ()
		elif infogathering ==  " 14 " :
			Crips ()
		elif infogathering ==  " 15 " :
			ท่าน()
		elif infogathering ==  " 16 " :
			evilURL ()
		elif infogathering ==  " 17 " :
			กองหน้า ()
		elif infogathering ==  " 18 " :
			xshell ()
		elif infogathering ==  " 19 " :
			owscan ()
		elif infogathering ==  " 20 " :
			osif ()
		elif infogathering ==  " 21 " :
			devploit ()
		elif infogathering ==  " 22 " :
			namechk ()
		elif infogathering ==  " 23 " :
			auxile ()
		elif infogathering ==  " 24 " :
			inther ()
		elif infogathering ==  " 25 " :
			ginf ()
		elif infogathering ==  " 26 " :
			gpstr ()
		elif infogathering ==  " 27 " :
			เอส ()
		elif infogathering ==  " 28 " :
			FIM ()
		elif infogathering ==  " 00 " หรือ infogathering ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()
	
	elif lazymux ==  " 2 " หรือ lazymux ==  " 02 " :
		พิมพ์ " \ n     [01] Nmap "
		พิมพ์ "     [02] AndroZenmap "
		พิมพ์ "     [03] AstraNmap "
		พิมพ์ "     [04] Easymap "
		พิมพ์ "     [05] Red Hawk "
		พิมพ์ "     [06] D-Tect "
		พิมพ์ "     [07] เครื่องสแกน SQLi Damn Small "
		พิมพ์ "     [08] SQLiv "
		พิมพ์ "     [09] sqlmap "
		พิมพ์ "     [10] sqlscan "
		พิมพ์ "     [11] Wordpresscan "
		พิมพ์ "     [12] WPScan "
		พิมพ์ "     [13] sqlmate "
		พิมพ์ "     [14] wordpresscan "
		พิมพ์ "     [15] WTF "
		พิมพ์ "     [16] Rang3r "
		พิมพ์ "     [17] กองหน้า"
		พิมพ์ "     [18] Routersploit "
		พิมพ์ "     [19] Xshell "
		พิมพ์ "     [20] SH33LL "
		พิมพ์ "     [21] BlackBox "
		พิมพ์ "     [22] XAttacker "
		พิมพ์ "     [23] OWScan \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		vulnscan =  raw_input ( " lzmx> " )

ถ้า vulnscan ==  " 01 " หรือ vulnscan ==  " 1 " :
			nmap ()
		elif vulnscan ==  " 02 " หรือ vulnscan ==  " 2 " :
			androZenmap ()
		elif vulnscan ==  " 03 " หรือ vulnscan ==  " 3 " :
			astraNmap ()
		elif vulnscan ==  " 04 " หรือ vulnscan ==  " 4 " :
			easyMap ()
		elif vulnscan ==  " 05 " หรือ vulnscan ==  " 5 " :
			เหยี่ยวแดง()
		elif vulnscan ==  " 06 " หรือ vulnscan ==  " 6 " :
			dtect ()
		elif vulnscan ==  " 07 " หรือ vulnscan ==  " 7 " :
			DSSS ()
		elif vulnscan ==  " 08 " หรือ vulnscan ==  " 8 " :
			sqliv ()
		elif vulnscan ==  " 09 " หรือ vulnscan ==  " 9 " :
			sqlmap ()
		elif vulnscan ==  " 10 " :
			sqlscan ()
		elif vulnscan ==  " 11 " :
			wordpreSScan ()
		elif vulnscan ==  " 12 " :
			wpscan ()
		elif vulnscan ==  " 13 " :
			sqlmate ()
		elif vulnscan ==  " 14 " :
			wordpresscan ()
		elif vulnscan ==  " 15 " :
			WTF ()
		elif vulnscan ==  " 16 " :
			rang3r ()
		elif vulnscan ==  " 17 " :
			กองหน้า ()
		elif vulnscan ==  " 18 " :
			routersploit ()
		elif vulnscan ==  " 19 " :
			xshell ()
		elif vulnscan ==  " 20 " :
			sh33ll ()
		elif vulnscan ==  " 21 " :
			กล่องดำ()
		elif vulnscan ==  " 22 " :
			xattacker ()
		elif vulnscan ==  " 23 " :
			owscan ()
		elif vulnscan ==  " 00 " หรือ vulnscan ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()
	
	elif lazymux ==  " 3 " หรือ lazymux ==  " 03 " :
		พิมพ์ " \ n     [01] Torshammer "
		พิมพ์ "     [02] Slowloris "
		พิมพ์ "     [03] Fl00d & Fl00d2 "
		พิมพ์ "     [04] GoldenEye "
		พิมพ์ "     [05] Xerxes "
		พิมพ์ "     [06] Planetwork-DDOS "
		พิมพ์ "     [07] ไฮดรา"
		พิมพ์ "     [08] Black Hydra "
		พิมพ์ "     [09] Xshell "
		พิมพ์ "     [10] santet-online \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		stresstest =  raw_input ( " lzmx> " )

if stresstest ==  " 01 " หรือ stresstest ==  " 1 " :
			torshammer ()
		elif stresstest ==  " 02 " หรือ stresstest ==  " 2 " :
			Slowloris ()
		elif stresstest ==  " 03 " หรือ stresstest ==  " 3 " :
			fl00d12 ()
		elif stresstest ==  " 04 " หรือ stresstest ==  " 4 " :
			ตาสีทอง()
		elif stresstest ==  " 05 " หรือ stresstest ==  " 5 " :
			Xerxes ()
		elif stresstest ==  " 06 " หรือ stresstest ==  " 6 " :
			planetwork_ddos ()
		elif stresstest ==  " 07 " หรือ stresstest ==  " 7 " :
			ไฮดรา ()
		elif stresstest ==  " 08 " หรือ stresstest ==  " 8 " :
			black_hydra ()
		elif stresstest ==  " 09 " หรือ stresstest ==  " 9 " :
			xshell ()
		elif stresstest ==  " 10 " :
			sanlen ()
		elif stresstest ==  " 00 " หรือ stresstest ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()
	
	elif lazymux ==  " 4 " หรือ lazymux ==  " 04 " :
		พิมพ์ " \ n     [01] ไฮดรา"
		พิมพ์ "     [02] FMBrute "
		พิมพ์ "     [03] HashID "
		พิมพ์ "     [04] Facebook Brute Force 3 "
		พิมพ์ "     [05] Black Hydra "
		พิมพ์ "     [06] Hash Buster "
		พิมพ์ "     [07] FBBrute "
		พิมพ์ "     [08] Cupp "
		พิมพ์ "     [09] InstaHack "
		พิมพ์ "     [10] WordList อินโดนีเซีย"
		พิมพ์ "     [11] Xshell "
		พิมพ์ "     [12] สังคม - วิศวกรรม"
		พิมพ์ "     [13] BlackBox "
		พิมพ์ "     [14] Hashzer "
		พิมพ์ "     [15] Hasher "
		พิมพ์ "     [16] Hash-Generator "
		พิมพ์ "     [17] nk26 "
		พิมพ์ "     [18] Hasherdotid "
		พิมพ์ "     [19] ขบเคี้ยว"
		พิมพ์ "     [20] Hashcat "
		พิมพ์ "     [21] ASU \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		passtak =  raw_input ( " lzmx> " )
		
		if passtak ==  " 01 " หรือ passtak ==  " 1 " :
			ไฮดรา ()
		elif passtak ==  " 02 " หรือ passtak ==  " 2 " :
			fmbrute ()
		elif passtak ==  " 03 " หรือ passtak ==  " 3 " :
			hashid ()
		elif passtak ==  " 04 " หรือ passtak ==  " 4 " :
			fbBrute ()
		elif passtak ==  " 05 " หรือ passtak ==  " 5 " :
			black_hydra ()
		elif passtak ==  " 06 " หรือ passtak ==  " 6 " :
			hash_buster ()
		elif passtak ==  " 07 " หรือ passtak ==  " 7 " :
			fbbrutex ()
		elif passtak ==  " 08 " หรือ passtak ==  " 8 " :
			Cupp ()
		elif passtak ==  " 09 " หรือ passtak ==  " 9 " :
			instaHack ()
		elif passtak ==  " 10 " :
			indonesian_wordlist ()
		elif passtak ==  " 11 " :
			xshell ()
		elif passtak ==  " 12 " :
			สังคม()
		elif passtak ==  " 13 " :
			กล่องดำ()
		elif passtak ==  " 14 " :
			hashzer ()
		elif passtak ==  " 15 " :
			Hasher ()
		elif passtak ==  " 16 " :
			hashgenerator ()
		elif passtak ==  " 17 " :
			nk26 ()
		elif passtak ==  " 18 " :
			hasherdotid ()
		elif passtak ==  " 19 " :
			กระทืบ ()
		elif passtak ==  " 20 " :
			hashcat ()
		elif passtak ==  " 21 " :
			เอส ()
		elif passtak ==  " 00 " หรือ passtak ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()

elif lazymux ==  " 5 " หรือ lazymux ==  " 05 " :
		พิมพ์ " \ n     [01] sqlmap "
		พิมพ์ "     [02] Webdav "
		พิมพ์ "     [03] xGans "
		พิมพ์ "     [04] Webdav Mass Exploit "
		พิมพ์ "     [05] WPSploit "
		พิมพ์ "     [06] sqldump "
		พิมพ์ "     [07] Websploit "
		พิมพ์ "     [08] sqlmate "
		พิมพ์ "     [09] sqlokmed "
		พิมพ์ "     [10] โซน"
		พิมพ์ "     [11] Xshell "
		พิมพ์ "     [12] SH33LL "
		พิมพ์ "     [13] XAttacker "
		พิมพ์ "     [14] XSStrike "
		พิมพ์ "     [15] Breacher "
		พิมพ์ "     [16] OWScan "
		พิมพ์ "     [17] ko-dork "
		พิมพ์ "     [18] ApSca "
		พิมพ์ "     [19] amox "
		พิมพ์ "     [20] FaDe "
		พิมพ์ "     [21] AUXILE "
		พิมพ์ "     [22] HPB "
		พิมพ์ "     [23] inther "
		พิมพ์ "     [24] Atlas \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		webhack =  raw_input ( " lzmx> " )
		
		if webhack ==  " 01 " หรือ webhack ==  " 1 " :
			sqlmap ()
		elif webhack ==  " 02 " หรือ webhack ==  " 2 " :
			WebDAV ()
		elif webhack ==  " 03 " หรือ webhack ==  " 3 " :
			xGans ()
		elif webhack ==  " 04 " หรือ webhack ==  " 4 " :
			webmassploit ()
		elif webhack ==  " 05 " หรือ webhack ==  " 5 " :
			wpsploit ()
		elif webhack ==  " 06 " หรือ webhack ==  " 6 " :
			sqldump ()
		elif webhack ==  " 07 " หรือ webhack ==  " 7 " :
			websploit ()
		elif webhack ==  " 08 " หรือ webhack ==  " 8 " :
			sqlmate ()
		elif webhack ==  " 09 " หรือ webhack ==  " 9 " :
			sqlokmed ()
		elif webhack ==  " 10 " :
			โซน ()
		elif webhack ==  " 11 " :
			xshell ()
		elif webhack ==  " 12 " :
			sh33ll ()
		elif webhack ==  " 13 " :
			xattacker ()
		elif webhack ==  " 14 " :
			xsstrike ()
		elif webhack ==  " 15 " :
			breacher ()
		elif webhack ==  " 16 " :
			owscan ()
		elif webhack ==  " 17 " :
			kodork ()
		elif webhack ==  " 18 " :
			apsca ()
		elif webhack ==  " 19 " :
			amox ()
		elif webhack ==  " 20 " :
			จาง ()
		elif webhack ==  " 21 " :
			auxile ()
		elif webhack ==  " 22 " :
			hpb ()
		elif webhack ==  " 23 " :
			inther ()
		elif webhack ==  " 24 " :
			Atlas ()
		elif webhack ==  " 00 " หรือ webhack ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()
	
	elif lazymux ==  " 6 " หรือ lazymux ==  " 06 " :
		พิมพ์ " \ n     [01] Metasploit "
		พิมพ์ "     [02] commix "
		พิมพ์ "     [03] sqlmap "
		พิมพ์ "     [04] โหดร้าย"
		พิมพ์ "     [05] A-Rat "
		พิมพ์ "     [06] WPSploit "  
		พิมพ์ "     [07] Websploit "
		พิมพ์ "     [08] Routersploit "
		พิมพ์ "     [09] BlackBox "
		พิมพ์ "     [10] XAttacker "
		พิมพ์ "     [11] TXTool "
		พิมพ์ "     [12] MSF-Pg "
		พิมพ์ "     [13] การหาประโยชน์ไบนารี"
		พิมพ์ "     [14] ASU \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		exploitool =  raw_input ( " lzmx> " )
		
		ถ้า exploitool ==  " 01 " หรือ exploitool ==  " 1 " :
			Metasploit ()
		elif exploitool ==  " 02 " หรือ exploitool ==  " 2 " :
			Commix ()
		elif exploitool ==  " 03 " หรือ exploitool ==  " 3 " :
			sqlmap ()
		elif exploitool ==  " 04 " หรือ exploitool ==  " 4 " :
			โหดร้าย ()
		elif exploitool ==  " 05 " หรือ exploitool ==  " 5 " :
			a_rat ()
		elif exploitool ==  " 06 " หรือ exploitool ==  " 6 " :
			wpsploit ()
		elif exploitool ==  " 07 " หรือ exploitool ==  " 7 " :
			websploit ()
		elif exploitool ==  " 08 " หรือ exploitool ==  " 8 " :
			routersploit ()
		elif exploitool ==  " 09 " หรือ exploitool ==  " 9 " :
			กล่องดำ()
		elif exploitool ==  " 10 " :
			xattacker ()
		elif exploitool ==  " 11 " :
			txtool ()
		elif exploitool ==  " 12 " :
			msfpg ()
		elif exploitool ==  " 13 " :
			binploit ()
		elif exploitool ==  " 14 " :
			เอส ()
		elif exploitool ==  " 00 " หรือ exploitool ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()

elif lazymux ==  " 7 " หรือ lazymux ==  " 07 " :
		พิมพ์ " \ n     [01] KnockMail "
		พิมพ์ "     [02] Spammer-Grab "
		พิมพ์ "     [03] Hac "
		พิมพ์ "     [04] สแปมเมอร์ - อีเมล์"
		พิมพ์ "     [05] SocialFish "
		พิมพ์ "     [06] santet ออนไลน์"
		พิมพ์ "     [07] SpazSMS "
		พิมพ์ "     [08] LiteOTP "
		พิมพ์ "     [09] ASU \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		sspoof =  raw_input ( " lzmx> " )
		
		if sspoof ==  " 01 " หรือ sspoof ==  " 1 " :
			knockmail ()
		elif sspoof ==  " 02 " หรือ sspoof ==  " 2 " :
			spammer_grab ()
		elif sspoof ==  " 03 " หรือ sspoof ==  " 3 " :
			HAC ()
		elif sspoof ==  " 04 " หรือ sspoof ==  " 4 " :
			spammer_email ()
		elif sspoof ==  " 05 " หรือ sspoof ==  " 5 " :
			socfish ()
		elif sspoof ==  " 06 " หรือ sspoof ==  " 6 " :
			sanlen ()
		elif sspoof ==  " 07 " หรือ sspoof ==  " 7 " :
			spazsms ()
		elif sspoof ==  " 08 " หรือ sspoof ==  " 8 " :
			liteotp ()
		elif sspoof ==  " 09 " หรือ sspoof ==  " 9 " :
			เอส ()
		elif sspoof ==  " 00 " หรือ sspoof ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()
	
	elif lazymux ==  " 8 " หรือ lazymux ==  " 08 " :
		พิมพ์ " \ n     [01] SpiderBot "
		พิมพ์ "     [02] Ngrok "
		พิมพ์ "     [03] Sudo "
		พิมพ์ "     [04] Ubuntu "
		พิมพ์ "     [05] Fedora "
		พิมพ์ "     [06] Kali Nethunter "
		พิมพ์ "     [07] VCRT "
		พิมพ์ "     [08] E-Code "
		พิมพ์ "     [09] Termux-Styling "
		พิมพ์ "     [10] PassGen "
		พิมพ์ "     [11] xl-py "
		พิมพ์ "     [12] BeanShell "
		พิมพ์ "     [13] WebConn "
		พิมพ์ "     [14] ขบเคี้ยว"
		พิมพ์ "     [15] Textr "
		พิมพ์ "     [16] AutoVisitor "
		พิมพ์ "     [17] RShell "
		พิมพ์ "     [18] TermPyter \ n "
		พิมพ์ "     [00] กลับสู่เมนูหลัก\ n "
		moretool =  raw_input ( " lzmx> " )
		
		if moretool ==  " 01 " หรือ moretool ==  " 1 " :
			Spiderbot ()
		elif moretool ==  " 02 " หรือ moretool ==  " 2 " :
			ngrok ()
		elif moretool ==  " 03 " หรือ moretool ==  " 3 " :
			sudo ()
		elif moretool ==  " 04 " หรือ moretool ==  " 4 " :
			อูบุนตู ()
		elif moretool ==  " 05 " หรือ moretool ==  " 5 " :
			ฟาง ()
		elif moretool ==  " 06 " หรือ moretool ==  " 6 " :
			nethunter ()
		elif moretool ==  " 07 " หรือ moretool ==  " 7 " :
			vcrt ()
		elif moretool ==  " 08 " หรือ moretool ==  " 8 " :
			ecode ()
		elif moretool ==  " 09 " หรือ moretool ==  " 9 " :
			stylemux ()
		elif moretool ==  " 10 " :
			passgencvar ()
		elif moretool ==  " 11 " :
			xlPy ()
		elif moretool ==  " 12 " :
			beanshell ()
		elif moretool ==  " 13 " :
			webconn ()
		elif moretool ==  " 14 " :
			กระทืบ ()
		elif moretool ==  " 15 " :
			textr ()
		elif moretool ==  " 16 " :
			autovisitor ()
		elif moretool ==  " 17 " :
			rshell ()
		elif moretool ==  " 18 " :
			termpyter ()
		elif moretool ==  " 00 " หรือ moretool ==  " 0 " :
			restart_program ()
		อื่น :
			พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
			หมดเวลา ( 2 )
			restart_program ()
	
	elif lazymux ==  " 10 " :
		sys.exit ()
	
	อื่น :
		พิมพ์ " \ nข้อผิดพลาด: อินพุตผิด"
		หมดเวลา ( 2 )
		restart_program ()

ถ้า __name__  ==  " __main__ " :
	หลัก()
