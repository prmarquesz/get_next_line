
<h1 align="center">📑 <a href="#">Get Next Line </a></h1>
<h3 align="center">My newest project as a cadet at École 42. This is my get next line function.</h3>
<h4 align="center">
	<b>Status</b>: Finished ✅🚀
</h4>
<p align="center">
	<a href="#About">About</a> •
	<a href="#Features">Features</a> •
	<a href="#How-it-works">How it works</a> • 
	<a href="#Author">Author</a>
</p>

## 💻 About <a name='About'></a>

📑 The goal of this project was to code a function that returns a line ending with a new line, read from a file descriptor.

### 🎯 Briefing

Part 				| Functions
-------------------	| --------- 
Mandatory Function	| get_next_line
Bonus Function		| get_next_line_bonus

---

## ⚙ Features <a name='Features'></a>
Function					| Behavior
---------------				| --------
get_next_line				| The function takes an index of a file descriptor (`fd`) along with a pointer to a string (`line`), reads x bits (specified in `BUFFER_SIZE`) from the file and returns 1 if there is a line break (\n), 0 if EOF (end of file) and -1 if there is an error
get_next_line_utils_bonus	| Same thing as get_next_line but in the bonus version it can get lines from more than one file

---

## 🚀 How it works <a name='How-it-works'></a>

### Clone this repository
```git
git clone https://github.com/prmarquesz/get_next_line.git
```
### Compilation
It is necessary to define the BUFFER_SIZE or add the following flag to the compilation flags: -D BUFFER_SIZE=xx
```c
gcc -D BUFFER_SIZE=32 main.c get_next_line.c get_next_line_utils.c
```
### Running the program
```c
./a.out
```

---

# 👨‍🚀 Author <a name='Author'></a>

<a href="#">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/69995036?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Paulo Roberto Marques</b></sub></a> <a href="#" title="Cadet">🚀</a>


Made with ❤️ by Paulo Roberto Marques 👋🏽  Get in Touch!

[![Linkedin Badge](https://img.shields.io/badge/-Paulo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/prmarquesz/)](https://www.linkedin.com/in/prmarquesz/) 
[![Instagram Badge](https://img.shields.io/badge/-prmarquesz-red?style=flat-square&logo=Instagram&logoColor=white&link=https://www.instagram.com/prmarquesz/)](https://www.instagram.com/prmarquesz/)