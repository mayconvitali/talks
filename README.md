Maycon Vitali Talks
===================

The objective of this repository is to join some of my talks on the same place.


Direct Access
-------------

| Released | Title | Link |
| -------- | ------ | ------ |
| 2019-06-18 | Reversing Android Applications | [Click Here](reversing-android-applications)
| 2018-11-26 | Attacking the Oracle: Debugging the Padding | [Click Here](padding-oracle-attack/) |
| 2018-10-26 | Internet of Sh!t - Hacking Embedded Devices | [Click Here](hacking-embedded-devices/) |
| 2017-03-27 | Smashing the Memory Protections | [Click Here](smashing-memory-protections/) |
| 2017-03-27 | Introdução à Exploração de Corrupção de Memória (portuguese) | [Click Here](intro-memory-corruption) |

Abstracts
-------------

- Reversing Android Applications
	
	Mobile Application has been become the main application on many fields, including sales, financial, retail etc. These application has their own classes of vulnerabilidades and a good start point to have some fun is reversing them. This talk gives a first steps on reversing android applications, showing some fundamentals, techniques and tools.

	This talk was presented on the first DC5527 Meeting.

- Attacking the Oracle: Debugging the Padding

	Padding Oracle Attack (PoA) is a cryptography attack commonly applied on CTF challenges and (why not?) applications on the wild. In this presentation, I explain the basics concepts and fundamentals of this technique and how we can apply it using the [paddingoracle](https://github.com/mwielgoszewski/python-paddingoracle) Python package.	

	This talk was presented on [BHack 2018](http://www.bhack.com.br/).

- Internet of Sh!t - Hacking Embedded Devices

	Embedded devices were present everywhere, since SmartWatches until SmartLamp. But what few people say/assume is that the buzzword Internet of Things (IoT) raise from the "gourmeting" of embedded devices.

	In this talk, I demonstrate the steps to exploit embedded devices since the retrieving of the firmware by downloading it on the vendor page or extracting directly from the flash memory (using SPI); the reverse engineering of some MIPS arcitecture binaries (ELF and bootload itself) and the analisys of the surface attack.

	This talk was initially presented on [Hackers to Hackers Conference (H2HC 2018)](https://www.h2hc.com.br/).

- Smashing the Memory Protections

	NX, ASLR and PIE are present in almost every modern Operating System. Contrary to popular belief, the goal of these protections is not to inhibit the exploration software, but reduce it. This talk intents to show how to bypass these protections, even if they have been used in combination to protect the binary and the environment itself.

- Introdução à Exploração de Corrupção de Memória

	(Portuguese) Exploração de Corrupção de memória ocorrem quando determinado conteúdo de memória é intencionalmente modificado por causa de falhas de programação. Essas falhas podem ocorrer desde em sistemas operacionais modernos até mini-dispositivos embarcados (como roteadores xDSL). Em sua apresentação, Maycon pretende introduzir de maneira técnica e clara alguns conceitos básicos necessários para um entendimento inicial do processo de exploração dessas vulnerabilidades, focando em exemplos escritos na Linguagem C.
