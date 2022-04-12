# Shokhrux Karimov


## Contact Info
* ### Address: Bobur st. Khorezm, Uzbekistan.
* ### Phone: +998 91 4262025
* ### Telegraph: [@khon_engineer](https://t.me/khon_engineer)
* ### Email: karimovshokhrux2001@gmail.com
* ### GitHub: [shokhruxkarimov](https://github.com/shokhruxkarimov/)
* ### CodePen: [shokhruxkarimov](https://codepen.io/Khon-Engineer)


## Summary

I'm studying in Tashkent Information of technology university in Uzbekistan, and I'm third year student. I've worked on some small web projects with my teachers, peers, and friends. I'm interested in Web technology, algorithms, math, and business, so that studying is my priority. I want to work with highly-experienced developers, work on huge projects and also want to create what can help to all over the world during my career. Right now, I'm studying in RS School to gain very important knowledge and experience and want to work in there.


## Skills

* HTML
* CSS(Bootstrap as an framework)
* Javascript(Basic fundamentals, functional programming, OOP, ES6)
* Version control: Git(Git Hub)
* C++(basic knowledge), Java(basic knowledge), 
* Computer science
* Editors: Sublime Text, Brackets, VSCode, Atom, CodeBlocks, Devc++
* Figma(basic knowledge)


## Code Examples

        class stack {  
          constructor(){  
              this.data = [];  
              this.top = 0;  
          }  
          stackpush(element) {  
            this.data[this.top] = element;  
            this.top = this.top + 1;  
          }  
          stacklength() {  
            return this.top;  
          }  
          peek() {  
            return this.data[this.top-1];  
          }  
          isEmpty() {  
           return this.top == 0;  
          }  
          stackpop() {  
          if( this.isEmpty() == false ) {  
             this.top = this.top -1;  
             return this.data.pop(); // last element gets deleted  
           }  
          }  
          print() {  
            var t = this.top - 1;   
            while(t >= 0) {   
                console.log(this.data[top]);  
                 t--;  
             }  
          }  
          reverse() {  
             this.rev (this.top - 1 );  
          }  
          rev(index) {  
             if(index != 0) {  
                this.rev(index-1);  
             }  
             console.log(this.data[index]);  
          }  
      }  

*I learned this code in order to learn data structures in Javascript. The code above is used to build Stack structure manually.*
