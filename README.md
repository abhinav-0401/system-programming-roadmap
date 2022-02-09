# System Programming Roadmap

A three year old roadmap to teach myself compiler dev, malware reverse engineering and kernel dev fundamentals. To be noted they are only for the fundamental knowledge and doesn't make you a master of any. I will pick one or more of the above mentioned fields for later research in some specific topics. [Low Level Programming University](https://github.com/gurugio/lowlevelprogramming-university) is also a great resource to follow but this is my personal roadmap.

Also note that you can still start another topic pretty easily even before finishing the previous ones (which im gona do for sure), given that there are not any prerequisites for it.

## Prerequisites

I'm already assuming that you have basic understanding of computer architecture and experience with atleast one system programming language, some basics of how assembly works and familiar using any POSIX system.

### System Programming Languages
- [C](https://beej.us/guide/bgc/)
- [Rust](https://doc.rust-lang.org/stable/book/)
- [C++](https://www.learncpp.com/)
- [C++ (video)](https://www.youtube.com/playlist?list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb)

### Learn some x86
If you are not familiar with assembly yet, I would recommend to check out some tutorials like-
- [Introduction to x86 assembly language by Davy on youtube](https://www.youtube.com/playlist?list=PLmxT2pVYo5LB5EzTPZGfFN0c2GDiSXgQe)
- [OMU x86_64 lessons](https://omu.rce.so/lessons/asm-x86-64/)
- [begin.re/](https://www.begin.re/)
- [x86 Asm](https://en.wikibooks.org/wiki/X86_Assembly)
- [The Art Of Asm](https://www.plantation-productions.com/Webster/www.artofasm.com/Linux/HTML/AoATOC.html)
- Even Manuals are great sources of learning.The manuals for processor can easily be found using a Google search ("Intel Manuals," "ARM manuals)
- After being comfortable with the concepts, [x86 instruction listings](https://en.wikipedia.org/wiki/X86_instruction_listings) on wikipedia will always be the goto guide for reference.
- And making C programs and reading the disassembly always helps to match patterns.
- [Article by 0x41 reversing for dummies](https://0x41.cf/reversing/2021/07/21/reversing-x86-and-c-code-for-beginners.html) to be able to reverse basic crackmes.

After this I would recommend to solve easy crackmes for exercise. [crackmes.one](https://crackmes.one) and tryhackme is a good place to find some of the easy ones. Hard ones still require some pwning knowledge which I'm gona discuss in the exploitation section.

### Compilers
- Read the [Dragon Book](https://en.wikipedia.org/wiki/Compilers:_Principles,_Techniques,_and_Tools).
- [Crafting Interpreters](https://craftinginterpreters.com/) is a good one for beginners.
- [Awesome Compilers](https://github.com/aalhour/awesome-compilers)
- Make an interpreted programming language.
- Make a source to source compiler (or transpiler).
- Try to make a compiled programming language targetting one architecture.
- Learn about the [LLVM toolchain](https://llvm.org/docs/)
- Try to follow the llvm tutorial to make your first programmging language using llvm backend.
- Make a Just In Time Compiler
- Experiment with the toolchain to create custom backends as well.
- My [discord server](https://discord.gg/RrDnEj6r9k) lang-dev section

### Exploitation
- [pwn.college](https://pwn.college) is the best learning resource I got so far for exploitation. From assembly to kernel exploitation, it covers it all.
- [OMU exploitation labs](https://omu.rce.so/gcc-2022/)
- [LiveOverflow's binexp series on youtube](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)
- [Tutorial by 0xinfection](https://0xinfection.github.io/reversing/)
- [Exploit dev on the infosec reference](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Exploit_Dev.md)
- [Windows exploit dev](https://github.com/FULLSHADE/WindowsExploitationResources)
- After learning about some exploitation, you can solve CTFs now. Some of them include:
  -  [pwnable.kr](https://pwnable.kr)
  -  [Overthewire wargames covering exploitation](https://overthewire.org/wargames)
  -  HackTheBox challenges based on binary exploitation

### Browser Exploitation and Development
- Development
  - [JavaScript bytecode VM Andreas Kling](https://www.youtube.com/playlist?list=PLMOpZvQB55beChggmvk-sUm8X_vSezpqL)
  - [Browser Parsing & JS AST Anderas Kling](https://www.youtube.com/playlist?list=PLMOpZvQB55be0Nfytz9q2KC_drvoKtkpS)
  - [How to build a virtual machine](https://www.youtube.com/watch?v=OjaAToVkoTw)
  - [Adventures in JIT compilation](https://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-1-an-interpreter/)
- Exploitation:
  - [Browser Exploition series by LiveOverflow](https://www.youtube.com/playlist?list=PLhixgUqwRTjwufDsT1ntgOY9yjZgg5H_t)
  - [Web Assembly Hacking talk Black Hat](https://www.youtube.com/watch?v=DFPD9yI-C70)
  - [Browser pwn on github](https://github.com/m1ghtym0/browser-pwn)
  - [Web Browser Exploitation- University of Florida](https://www.youtube.com/watch?v=-bfO-b5gzHc)


### Malware
- [Practical Malware Analysis](https://www.amazon.in/Practical-Malware-Analysis-Hands-Dissecting/dp/1593272901)
- [Malware analysis bootcamp by hackersploit](https://www.youtube.com/playlist?list=PLBf0hzazHTGMSlOI2HZGc08ePwut6A2Io)
- After learning basics of malware reversing and behaviour, you can now move to reversing some real samples of those.
- [Labs by Malware Unicorn](https://malwareunicorn.org/#/workshops)
- [VX Underground - The largest collection of malware source code, samples, and papers on the internet.](https://www.vx-underground.org/)
- [Malware section from the infosec reference](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Malware.md)

### Todo
- Kernel Dev
