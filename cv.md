#Zuev Roman#
###General information###
####Date of birth####
12.11.1986
####Adress####
Russia,Moscow
###Contacts###
####Telegram####
@zuevra
####Mail####
+799*40472**@gmail.com
####Phone####
+799*40472**
####Discord####
zr0man
###About me###
Hello, everyone, i'm Roman. Now I work as a PM in marketing. I am interested in programming.
###Education###
No comments
###My skills###
No comments
###Example code###
```begin
var a : array[1..50] of integer;
var m1 : integer;  
var m2 : integer; 
var buff : integer;   
var n :=readinteger;
for var i:=1 to n do readln(a[i]);
if a[1]>a[2]
 then begin
     m1:=1;
     m2:=2;
   end
   
   else begin
     m1:=2;
     m2:=1;
  end;
  for var i:=3 to n do
  if a[i]>a[m1] then begin
  buff:=m1;
       m1:=i;
      if a[buff]>a[m2] then
           m2:=buff;
       end
       else
         if a[i]>a[m2] then
           m2:=i;     
  println(m1);
  println(m2);
end.
```