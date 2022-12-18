# Nikolai Roshchin 

## Contacts

Location: Finland, 48350 Kotka  
Phone: +358 466 144 766  
e-mail: nikolai.roshchin@gmail.com  
https://www.linkedin.com/in/nikolai-roshchin/  
__________________________________________________________________  

## About me

I am a physics engineer by education. Graduated Petrozavodsk State University in 1996 after which worked as software engineer in Karellestorg company. Then I was an maintanence engineer but one way or another my work was related with computers, networks and programming. Now I would like to return to my first profession.
I study Ruby and Ruby on Rails by myself. In december 2022 I passed the Fullstack developer course by dualboot partners.

## Skills

* Ruby 
* Ruby on Rails
* HTML
* Cascading Style Sheets (Basic)
* JavaScript (Basic)
* SQL (Basic)
* Problem Solving

## Code Example

Solution in Ruby  
[parseInt() reloaded Kata](https://www.codewars.com/kata/525c7c5ab6aecef16e0001a5)
```

def parse_int(string)  
  numbers = {  
    "zero" => 0, "one" => 1, "two" => 2, "three" => 3,  
    "four" => 4, "five" => 5, "six" => 6, "seven" => 7,  
    "eight" => 8, "nine" => 9, "ten" => 10, "eleven" =>11,  
    "twelve" => 12, "thirteen" => 13,  "fourteen" => 14, "fifteen" =>15,  
    "sixteen" => 16, "seventeen" =>17, "eighteen" => 18, "nineteen" => 19,  
    "twenty" => 20, "thirty" => 30, "forty" => 40, "fifty" => 50,  
    "sixty" => 60, "seventy" => 70, "eighty" => 80, "ninety" => 90,  
    "hundred" => 100, "thousand" => 1000, "million" => 1000000}  
  m, n = 0  
  summa = Array.new(0)  
  string. gsub!(/-| and /, ' ')   
  string. split. each do |x|   
     
     n = numbers[x]
     case n
       when 100
         m *= n
       when 1000, 1000000
         summa << (m * n)
         m = 0
     
       else  
         m += n  
     end  
   end  
   
  return m + summa. sum  
end  

```

## Experience

07/2022 – 12/2022 **Dualboot Partners Fullstack programmer course** (Ruby On Rails + React, Redux)  
In the process of studying was written
[Task Manager](https://github.com/nikolairoshchin/TaskManager) application.
The following tools and technologies were used:  
* HTML
* CSS
* Slim
* Ruby
* Ruby on Rails
* JavaScript
* React
* Redux
* Material UI
* Docker
* Docker Compose
* Git
* Github Actions
* Sidekiq
* Functional programming
* State machine

06/1997 – 08/1998 **KarelLesTorg** Software Engineer  
                  Development and support accounting software on Clipper for DOS.  
                  Administrate and support local area network (Novell NetWare)  

## Education

* 07/2022 – 12/2022  
Dualboot Partners Fullstack programmer (Ruby On Rails + React, Redux)  
* 10/2021 – Present  
Self-educated Ruby | Ruby on Rails  
* 05/2019 – 07/2019  
Aikuiskoulutuskeskus, Kouvola, Sähköalan täydennys- ja päivityskoulutus  
* 09/2016 – 12/2017  
EKAMI Sähkö- ja automaatiotekniikan perustutkinto (Basics of Electric and Automatic)  
* 09/1991 – 06/1996  
Petrozavodsk State University (PetrSU), Bachelor's degree, Engineering Physics/Applied Physics  

## Languages
* English - B2 Upper Intermediate  
[EF SET English Certificate 60/100 (B2 Upper Intermediate)](https://www.efset.org/cert/2EgLE4)

* Russian - native
* Finnish - YKI testi keskitaso (B1 Intermediate)

