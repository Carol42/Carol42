## C
```c
#include <stdio.h>

int main() { 
    printf("Hello World!");
return 0;
}
```

## C++
```c++
#include <iostream>

int main() {
	std::cout << "Hello World!";
	return 0;
}
```

## C#
```csharp
namespace HelloWorld
{
	class Hello {		
		static void Main(string[] args)
		{
			System.Console.WriteLine("Hello World!");
		}
	}
}
```

## Python
```py
print("Hello World!")
```

## Lua
```lua
print "Hello world!"
```

## MSDOS
```dos
ECHO Hello World!
```

## Bash (Unix Shell)
```bash
echo "Hello World!"
```

## Assembly
```
    global _main
    extern _printf

    section .text
_main:
    push    message
    call    _printf
    add        esp, 4
message:
    db    'Hello World!', 10, 0
```

## Java
```java
/*package whatever */

import java.io.*;

class GFG {
	public static void main (String[] args) {
	System.out.println("Hello World!");
	}
}
```

## Kotlin
```kotlin
fun main(args : Array<String>) {
    println("Hello world!")
}
```

## Swift
```swift
println("Hello, world!")
```

## LaTeX
```latex
\documentclass{article}
\begin{document}
Hello World!
\end{document}
```

## JavaScript
```js
console.log("Hello World!");
```
```js
document.write("Hello World!");
```

## TypeScript
```ts
console.log('Hello World!');
```

## Node.js
```js
var sys = require('sys');
sys.puts('Hello World!');
```

## R
```r
cat('Hello World!')
```

## HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Hello World!</title>
    </head>
    <body>
        <h1>Hello World!<h1>
    </body>
</html>
```

## PHP
```php
<?php
    echo "Hello World!";
?>
```

## Pascal
```pascal
program Hello;
begin
  writeln ('Hello world!');
end.
```

## CoffeeScript
```coffee
console.lof 'Hello World!'
```
```coffee
alert "Hello World!"
```

## Matlab
```matlab
disp('Hello World!');
```

## Cobol
```
*****************************
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO.
ENVIRONMENT DIVISION.
DATA DIVISION.
PROCEDURE DIVISION.
MAIN SECTION.
DISPLAY "Hello World!"
STOP RUN.
****************************
```

## Arduino Programming Language
```c++
void setup() {
  Serial.begin(9600);
  Serial.println("Hello World!");
}
void loop() {
  
}
```

## Scala
```scala
object HelloWorld extends App {
	printIn("Hello World!")
}
```

## Delphi
```delphi
program HelloWorld;
begin
  WriteLn('Hello World!');
end.
```

## Dart
```dart
main(){
	print('Hello World!');
}
```

## Haskell
```haskell
module Main where

main :: IO ()
main = putStrLn "Hello World!"
```

## Ruby
```ruby
puts 'Hello World!'
```

## Go
```go
println("Hello World!");
```

## F#
```fsharp
printfn "Hello World!"
```

## Lisp
```lisp
(print "Hello World!")
```

## MySQL Function
```sql
DELIMITER $$
CREATE FUNCTION hello_world() RETURNS TEXT COMMENT 'Hello World'
BEGIN
  RETURN 'Hello World';
END;
$$
DELIMITER ;
 
SELECT hello_world();
```

## PostgreSQL
```sql
CREATE FUNCTION hello_world() RETURNS text AS $$
BEGIN
RETURN 'Hello World';
END
$$ LANGUAGE plpgsql;

SELECT hello_world();
```

## Prolog
```prolog
hello :- display('Hello World!') , nl .
```

## BASIC
```basic
PRINT "Hello World!"
```

## Portugol
 ```
algoritmo "Hello World"
var
inicio
escreva ("Hello World!")
fimalgoritmo
 ```

## Portugol Studio
```
programa 
{ 
	funcao inicio () 
	{
		escreva("Hello World!\n")
	} 
}
```

## VisuAlg
```
algoritmo "OlaMundo"
inicio
    escreval("Hello World!")
fimalgoritmo
```

## Algol
```
BEGIN DISPLAY("Hello World!") END.
``` 

## Perl
```perl
#!/usr/bin/perl
print "Hello World!";
```

## TCL
```tcl
puts "Hello World!"
```

## Fortran
```fortran
PROGRAM HELLO
      WRITE (*,100)
      STOP
  100 FORMAT (' Hello World! ' /)
      END
```

## SVG

```svg
<?xml version="1.0" encoding="utf-8" standalone="no"?>
<!-- Hello World in SVG -->

<svg width="240" height="100" viewBox="0 0 240 100" zoomAndPan="disable"
     xmlns="http://www.w3.org/2000/svg"  xmlns:xlink="http://www.w3.org/1999/xlink">
  <title>Hello World!</title>
    <g>
      <text x="10" y="50">Hello World!</text>
      <animate attributeName='opacity' values='0;1' dur='4s' fill='freeze' begin="0s"/>
    </g>
</svg>
```

## Brainfuck
```brainfuck
++++++++++[>+++++++>++++++++++>+++<<<-]>++.>+.+++++++
..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.
```

## Human

||||
|-|-|-|
|Afrikaans|	Hallo, wêreld!|
|Albanian|	Pershëndetje Botë|
|Arabic	|أهلاً بالعالم	|(Ahlan bil 'Alam)|
|Armenian|	Բարե՛ւ, աշխարհ։|	(barev ash'kharh)|
|Azeri|	Salam Dünya|
|Czech|	Ahoj Světe!|
|Basque/Euskara|	Kaixo mundua!|
|Belarusian|	Прывітанне свет	|(Pryvitannie sviet)|
|Bemba|	Shani Mwechalo!|
|Bengali|	Shagatam Prithivi!|
|Bosnian|	Zdravo Svijete!|
|Bulgarian|	Здравей, свят!|	(Zdrav'ei svi'at)|
|Cambodian|	ជំរាបសួរ ពិភពលោក|	(chomreabsuor piphoplok)|
|Catalan|	Hola món!|
|Chinese|	你好世界|	(nǐ hǎo shì jiè)|
|Cherokee|	ᎣᏏᏲ ᎡᎶᎯ	|(O-si-yo E-lo-hi)|
|Chinook Wawa|	Klahowya Hayas Klaska|
|Croatian|	Bok Svijete!|
|Danish|	Hej, Verden!|
|Dutch|	Hallo, wereld!|
|English|	Hello World!|
|Esperanto|	Saluton mondo!|
|Estonian|	Tere maailm!|
|Finnish|	Hei maailma!|
|French|	Salut le Monde!|
|Frisian|	Hallo, wrâld!|
|Galician|	Ola mundo!|
|German|	Hallo Welt!|
|Greek|	Γεια σου κόσμε!|	(Geia soy kosme)|
|Hawaiian|	Aloha Honua|
|Hebrew|	שלום עולם	|(Shalom Olam)|
|Hindi|	नमस्ते दुनिया	|(namaste duniya)|
|Hmong|	Nyob zoo ntiaj teb.|
|Hungarian|	Helló világ!|
|Icelandic|	Halló heimur!|
|Igbo|	Ndewo Ụwa|
|Indonesian|	Halo Dunia!|
|Irish|	Dia dhaoibh, a dhomhain!|
|Italian|	Ciao Mondo!|
|Japanese|	こんにちは、 世界！	|(konnichiwa sekai)|
|Kannada|	ಹಲೋ ವರ್ಲ್ಡ್	|(Halō varlḍ)|
|Kiswahili|	Habari dunia!|
|Kikuyu|	Niatia thi!|
|Klingon|	nuqneH|
|Korean|	반갑다 세상아	|(bangabda, sesangah)|
|Lao|	ສະບາຍດີ,ໂລກ	|(sabaidi olk)|
|Latin|	AVE MVNDE	|(ave munde)|
|Latvian|	Sveika, Pasaule!|
|Lithuanian|	Sveikas, Pasauli|
|Lojban|	coi li terdi|
|Luxembourgish|	Moien Welt!|
|Malagasy|	Manao ahoana ry tany!|
|Malayalam|	Namaskaram, lokame|
|Maltese|	Merhba lid-dinja|
|Norwegian|	Hallo verden!|
|Persian|	!سلام دنیا	|(Salaam Donyaa!)|
|Polish|	Witaj świecie!|
|Portuguese|	Olá, mundo!|
|Punjabi|	ਸਤਿ ਸ੍ਰੀ ਅਕਾਲ ਦੁਨਿਆ	|(Sati srī akāla duni'ā)|
|Romanian|	Salut lume!|
|Russian|	Здравствуй, мир!|	(Zdra'vstvuj mi'r)|
|Scots Gaelic|	Halò, a Shaoghail!|
|Serbian|	Zdravo Svete!|
|Slovak|	Ahoj, svet!|
|Slovenian|	Pozdravljen svet!|
|Spanish|	¡Hola mundo!|
|Swedish|	Hallå världen!|
|Tagalog|	Kamusta mundo!|
|Tamil|	ஹலோ உலகம்	|(Halō ulakam)|
|Telugu|	హలో వరల్డ్	|(Halō varalḍ)|
|Thai|	สวัสดีโลก!	|(sawadee lok)|
|Turkish|	Merhaba Dünya!|
|Ukrainian|	Привiт, свiте!|	(Pryvi't svi'te)|
|Urdu|	ہیلو دنیا والو
|Vietnamese|	Xin chào thế giới|
|Welsh|	S'mae byd!|
|Yiddish|	העלא וועלט	|(hela velt)|
|Zulu|	Sawubona Mhlaba|


See more in my [Hello-World repo](https://github.com/Carol42/hello-world)!
