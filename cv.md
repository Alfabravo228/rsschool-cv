# Bohdan Mykhailenko 

### Currently
_I am a first year student from Ukraine.I have been learning WEB-development about 6 month.I hope to become a frontend-developer and for this target I will make an enough efforts.  I may master a big stream of new information , also I have an analytic type of mind.I have began to study English ,because I had very gap of knowledge in this._
___
### Skills
* Programming language:
  * Basics C/C++
  * Basics JavaScript(ES6)
  * Basics Python
* WEB-instuments:
  * HTML5
  * CSS(SCSS)
  * Basics Git/GitHub
___
### Example of coding 
```
##### JavaScript:

function findShort(s){
  let arr = [];
  let arr2 = [];
  let tmp = 0;
  arr = s.split('');

  for(let i = 0; i < arr.length; i++) {
    if( i == arr.length - 1 ) {
      tmp++;
      arr2.push(tmp);
      tmp = 0;
    }

    if(arr[i] != " ") {
      tmp ++;
    } else {
      arr2.push(tmp);
      tmp = 0;
    }
  }
  
  arr2.sort( (a, b) => a - b );
  return arr2[0];
} 
```
##### C++:
```
#include <iostream>
#include <windows.h>
#include <time.h>
#include <stdlib.h>
#include <conio.h> 

using namespace std;
HANDLE console = GetStdHandle(STD_OUTPUT_HANDLE); 
int number;

int main()
{
do {	
  srand(time(NULL));

  COORD position;                                     
  HANDLE hConsole = GetStdHandle(STD_OUTPUT_HANDLE);
  position.X = (rand() % 100 + 1);                                
  position.Y = (rand() % 30 + 1);                                
  SetConsoleCursorPosition(hConsole, position);

  int i, color; 
  string text = "Hello?World!";

  for ( i = 0; i < text.length(); i++) {
    color = (rand() % 15 + 1);
    SetConsoleTextAttribute(console, color); 
    cout << text[i]; 
    Sleep(333);
  }
  Sleep(1000);

  SetConsoleTextAttribute(console, 15); 
  system ("cls");

  cout<<"Do you want to continue?1/0"<<"\n";
  cin>>number;
  system ("cls");
} while (number == 1);
return 0;
getch();
}
```
___
### Experience
I don't have an experience in real projects,but I have made about 10 learning-project that is psd-makets.
___
### Education 
* School
* First course of university;specialty:System Analysis
* Online-courses for HTML/CSS/JavaScript
___
### English 
I learn English every day in order to improve my knowledge.Today,my level of English is intermediate.
___
### Contact
###### Email: _6alfabravo9@gmail.com_
###### Phone: _+380956450247_
###### Location: _Malyn,Ukraine_
___
