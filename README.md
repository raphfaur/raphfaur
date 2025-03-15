<h1 align="center" >Welcome all !</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/raphaël-faure">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" >
  </a>
  <a href="https://twitter.com/raphFaur">
  <img src="https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white" >
  </a>
  <a href="https://t.me/fwsub">
  <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" >
  </a>
</p>

<h2 align="center" > My main skills </h2>
<p align="center">
  <img src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Haskell-5e5086?style=for-the-badge&logo=haskell&logoColor=white" />
  <img src="https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white"/>
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  <img src="https://img.shields.io/badge/Qiskit-%236929C4.svg?style=for-the-badge&logo=Qiskit&logoColor=white" />
</p>

<h2 align="center" >Who am I ? 🧑‍💻 </h2>
<p align="center">
I'm a 20 yo French IT student at Paris-Saclay University 👨‍🎓 I live in Paris and love spending my time coding and discovering all kind of stuff !
Until January 2024, I worked as a network architect and administrator for AS 212424 ~ ViaRezo IP for a whole year. This was an opportunity for me to learn planty of things about clusters, low-level and high-level networking, virtualization and databases.
</p>


<h2 align="center" > What do I like ? 😎 </h2>
<p align="center">
I'm passionate about many things but my favorite thing at the moment is low level development. Let's have a look at a couple of projects I participated in !
</p>

<!-- 
Kernel dev
-->

<h2 align="center" > Kernel development 0️⃣1️⃣ </h2> 
<p align="center" > 💻 Language : <code>Rust</code> <code>x86 Assembly</code> </p> 
<p align="center" > 🛠️ Features : MBR, ext4 fs, PIC, I/O APIC, BIOS </p> 
<p align="center">
With a friend <a href="https://github.com/sleiderr">@sleiderr</a>, we wanted to learn how do a computer boot. I personnaly began by writing an x86 ASM bootloader and then we decided to try to do it in Rust. We first collaborated to write our own bootloaders and then decided to work together on a common project : we decided to found <a href="https://github.com/frozenpeach-dev">frozenpeach</a> to develop common projects.
</p>
<ul list-style-type="none" align="center">
  <a href = "https://github.com/raphfaur/bootloader" > The first bootloader </a> <br/>
  <a href = "https://github.com/frozenpeach-dev/bootloader" > The common bootloader </a>
</ul>

<!-- 
Debugger
-->

<h2 align="center" > Debugger and test framework ✔️ </h2> 
<p align="center" > 💻 Language : <code>Rust</code> <code>x86 Assembly</code> </p> 
<p align="center" > 🛠️ Features : gdb, rust-gdb, qemu, ld linker</p> 

<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/frozenpeach-dev/debugger" > An embedded Rust test framework </a> <br/>
    In order to debug and run test in our embedded Rust bootloader, we needed a custom test framework that could start a Qemu instance and automatically analyse execution flow.
    I also developped procedural macro to easily integrate tests in the main project. Not in production yet.
  </p>
</ul>


<!-- 
Compiler
-->

<h2 align="center" > Compiler theory training course 📚 </h2> 
<p align="center" > 💻 Language : <code>C</code></p> 

<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/compiler" > My compiler theory exercises </a> <br/>
    I'm currently interested in compiler and interpreter theory and I started training with the well-known book "Modern Compiler Implementation in C" by ANDREW W. APPEL. This repository is where I code the exercices given by the author.
  </p>
</ul>

<!-- 
Network dev
-->

<h2 align="center" > Low-level network development 🔌 </h2> 
<p align="center" > 💻 Language : <code>Rust</code> <code>C++</code> <code>C</code> </p> 
<p align="center" > 🛠️ Features : DHCP, loadbalancing</p> 
<p align="center">
As I said before, I used to be a network architect and administrator and I had to deal with networking issues. I'm thus interested in networking development. 
</p>
<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/frozenpeach-dev/dhcp" > A Rust DHCP </a> <br/>
    With <a href="https://github.com/frozenpeach-dev">frozenpeach</a> and <a href="https://github.com/sleiderr">@sleiderr</a> again we started the development of a Rust DHCP. I mainly worked on a <strong>high speed database</strong> with both hot and cold storage allowing fast and afe access to DHCP Leases.
  </p>

  <p>
    <a href = "https://github.com/raphfaur/loadbalancer" > A C++ Loadbalancer </a> <br>
  I worked a lot with HAProxy, that's why I started developing a loadbalancer in C++
  </p>
</ul>

<!-- 
Python ML and Cyber
-->

<h2 align="center" > ML 📈 and Cybersecurity 🔒</h2> 
<p align="center" > 
  💻 Language : <code>Python</code>  
</p> 
<p align="center" > 🛠️ Features : Neural networks, audio procesing</p> 
<p align="center">
I'm also interested in cybersecurity and machine learning.
</p>
<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/keyboard-eavesdropping" > Keyboard eavesdropping</a> <br/>
    I managed to reproduce a keayboard eavesdropping using neural networks, whitout using any library.
  </p>
</ul>

<!-- 
Web dev
-->

<h2 align="center" > Full stack development 🌐 </h2> 
<p align="center" > 💻 Language : <code>React</code> <code>ExpressJS</code></p> 
<p align="center">
As an administrator of an Internet Provider, I had to fix and improve wesites for our clients. In this context I learned backend and frontend development.
</p>
<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/frozencloud" > Photo cloud </a> <br/>
    As an easy example of what I can produce, I developped in a few days a authenticated photo cloud in React and Express.
  </p>
</ul>

<hr>

<h2 align="center" > Technologies I'm used to </h2>
<p align="center">
  <img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
  <img src="https://img.shields.io/badge/Openstack-%23f01742.svg?style=for-the-badge&logo=openstack&logoColor=white"/>
  <img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/datadog-%23632CA6.svg?style=for-the-badge&logo=datadog&logoColor=white" />
  <img src="https://img.shields.io/badge/ovh-%23123F6D.svg?style=for-the-badge&logo=ovh&logoColor=#123F6D" />
  <img src="https://img.shields.io/badge/ubiquiti-%230559C9.svg?style=for-the-badge&logo=ubiquiti&logoColor=white" />
</p>

<h2 align="center" > Tools I'm used to </h2>
<p align="center">
  <img src="https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white" />
  <img src="https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white"/>
  <img src="https://img.shields.io/badge/CLion-black?style=for-the-badge&logo=clion&logoColor=white" />
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white">
  <img src="https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black">
</p>




