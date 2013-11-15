HUDWAY Localization
===

If you want to help improve HUDWAY [http://hudwayapp.com] add your native language in the application. 
You are free to make a translation of the application interface. 
For this, make following instruction:

**Note.** Please contact us if you want to add your translation by sending an email - [iOS@russianit.ru]

To translate the application you should be:
---

**Note.** If you don't want translate files locally on your computer, you can translate files on GitHub, use web-based instruments for file editing

1. install git-client(SmartGit [http://www.syntevo.com/smartgithg/] or another git client)
2. download files from repositories
	SmartGit:
	- open smart git
	- select project > Clone
	- in opened window insert URL to repository [https://github.com/Tilium/HUDWAY_Localization.git] and press continue
	- press continue again
	- select local folder for copy repository files on your computer and press continue
	- set project name(any name title) and press finish

3. open folder with repository files
4. open or create new localization directory
	for example: 
		for English localization - en.lproj
		for Russian localization - ru.lproj
	List of localization folders:
```
		0. English         en
		1. French          fr
		2. German          de
		3. Italian         it
		4. Dutch           nl
		5. Swedish         sv
		6. Spanish         es
		7. Danish          da
		8. Portuguese      pt
		9. Norwegian       nb
		10. Hebrew          he
		11. Japanese        ja
		12. Arabic          ar
		13. Finnish         fi
		14. Greek           el
		15. Icelandic       is
		16. Maltese         mt
		17. Turkish         tr
		18. Croatian        hr
		19. Chinese         zh
		20. Urdu            ur
		21. Hindi           hi
		22. Thai            th
		23. Korean          ko
		24. Lithuanian      lt
		25. Polish          pl
		26. Hungarian       hu
		27. Estonian        et
		28. Latvian         lv
		29. Sami            se
		30. Faroese         fo
		31. Farsi           fa
		32. Russian         ru
		33. Chinese         zh
		34. Dutch           nl
		35. Irish           ga
		36. Albanian        sq
		37. Romanian        ro
		38. Czech           cs
		39. Slovak          sk
		40. Slovenian       sl
		41. Yiddish         yi
		42. Serbian         sr
		43. Macedonian      mk
		44. Bulgarian       bg
		45. Ukrainian       uk
		46. Byelorussian    be
		47. Uzbek           uz
		48. Kazakh          kk
		49. Azerbaijani     az
		50. Azerbaijani     az
		51. Armenian        hy
		52. Georgian        ka
		53. Moldavian       mo
		54. Kirghiz         ky
		55. Tajiki          tg
		56. Turkmen         tk
		57. Mongolian       mn
		58. Mongolian       mn
		59. Pashto          ps
		60. Kurdish         ku
		61. Kashmiri        ks
		62. Sindhi          sd
		63. Tibetan         bo
		64. Nepali          ne
		65. Sanskrit        sa
		66. Marathi         mr
		67. Bengali         bn
		68. Assamese        as
		69. Gujarati        gu
		70. Punjabi         pa
		71. Oriya           or
		72. Malayalam       ml
		73. Kannada         kn
		74. Tamil           ta
		75. Telugu          te
		76. Sinhalese       si
		77. Burmese         my
		78. Khmer           km
		79. Lao             lo
		80. Vietnamese      vi
		81. Indonesian      id
		82. Tagalog         tl
		83. Malay           ms
		84. Malay           ms
		85. Amharic         am
		86. Tigrinya        ti
		87. Oromo           om
		88. Somali          so
		89. Swahili         sw
		90. Kinyarwanda     rw
		91. Rundi           rn
		92. Nyanja            
		93. Malagasy        mg
		94. Esperanto       eo
		128. Welsh           cy
		129. Basque          eu
		130. Catalan         ca
		131. Latin           la
		132. Quechua         qu
		133. Guarani         gn
		134. Aymara          ay
		135. Tatar           tt
		136. Uighur          ug
		137. Dzongkha        dz
		138. Javanese        jv
		139. Sundanese       su
		140. Galician        gl
		141. Afrikaans       af
		142. Breton          br
		143. Inuktitut       iu
		144. Scottish        gd
		145. Manx            gv
		146. Irish           ga
		147. Tongan          to
		148. Greek           el
		149. Greenlandic     kl
		150. Azerbaijani     az
		151. Nynorsk         nn
 ```
 	If you create new .lproj directory, copy all files from en.lproj directory to your new localization directory

5. Open .lproj directory. Directory contains localization files for application pages, alerts, processes and other
6. Open any file. Files includes string lines with format:
	"application string key" = "localization string";
	translate need only "localization string"
7. after you translated and saved all files on your localization directory, open git-client and save changes in repository.
	In SmartGit:
	- open HUDWAY localization project on git-client
	- click to button "pull"
	- if opened configuration window, select "rebase" option ans click "configuration"
	- click on opened window button "pull"
	- wait when pull process is ended
	- click to button "commit"
	- enter "commit message", when enter your activity with files(for example "update english localization")
	- click button "Commit & push"
	- wait when commit process is ended
