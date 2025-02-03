## 👋
```assembly
section        .text         
global         _start          
_start:
    mov edx, len 
    mov ecx, msg 
    mov ebx, 1
    mov eax, 4
    int 0x80
    mov eax, 1
    int 0x80
section        .data             
    msg        db "Sugeng rawuh, rencang-rencang sedaya!", 0xa
    len        equ $ -msg
```

I'm Nayaka, a (self-proclaimed) hard-working informatics engineering student from Bandung Institute of Technology, eager to explore various branches of computer science and to satisfy my personal curiosity. Currently, I'm focusing on data science and cybersecurity. I've got experience in several programming languages and tools, and proficient in LaTeX typesetting.

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nayakazna&show_icons=true&theme=dracula" alt="Nayaka's GitHub stats">
</div>

## Languages

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nayakazna&hide=jupyter%20notebook,tex,html,css&theme=dracula&layout=compact&hide_border=true&exclude_repo=Upsolve-THT_GCS25_Nayaka" alt="Top Langs"/><br>
    <img src="https://skillicons.dev/icons?i=c,cpp,fortran,go,haskell,java,js,py,r" alt="Programming Languages" />
  </a>
</p>


## Tools
### Web Development
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,fastapi,threejs,react,supabase,vite" />
  </a>
</p>

### Machine Learning
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=sklearn,tensorflow" />
  </a>
</p>

### Robotics Software Control
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=arduino,opencv,ros" />
  </a>
</p>

### Miscellaneous
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vim,latex,obsidian,vscodium" />
  </a>
</p>
