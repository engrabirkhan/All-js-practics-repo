# All-js-practics-repo
----------------------------------------------

MODIUL 7 LIVE CLASS 1
---------------------------------------------
varible
--------------------
data type-

data type off varible

PRIMITIVE DATA TYPE
----------------------------

string
number
boolean
undefind
null

NON-PRIMITIVE DATA TYPE
------------------------------
object
array
reg exp
----------------------
operator



MODIUL 7 LIVE CLASS 2
--------------------------------------------















{   LOOP

1.FOR LOOP
2.WHILE LOOP
3.DO WHILE LOOP
4.for in loop,
 5.for of loop,
6.for each loop

7.FUNCATION
------------------------------------

8  PARAMETER ARGUMENT
-----------------------------------------
9.FUNCATION RETURN
-----------------------------------------
10.IIF /   ANONYMOUS FUNCATION
-----------------------------------------
11.ARROW/ LAMDA FUNCATION
----------------------------------------
12.ARROW INLINE FUNCATION
}























-----------------------
FOR LOOP                  for(i=0;i<10;i=i+1){

        let btn=`<button>${i}click me</button>`;
        document.write(btn);
        console.log("hello world");
     }
 _______________________________________________________



WHILE LOOP


        var i=0;
        while(i<10){
            
        let btn=`<button>${i}while </button> <br>`;
        document.write(btn);
        i=i+1;
        }






DO WHILE LOOP




    var i=0;
        do{
        let btn=`<button>${i}do while </button> <br>`;
        document.write(btn);
        i=i+1;
        }while(
            i<10
        )


        FUNCATION
---------------------------------------------

                     function addtwonumber(){
                     let a=10;
                        let b=20; 
                        let c=a+b;
                        document.write(c);
           }                                       
               addtwonumber();
        

    
        PARAMETER ARGUMENT
 -------------------------------------

               function addtwonumber(c,d){
                     let num1=c;
                        let num2=d; 
                        let sum=num1+num2;
                        document.write(sum+ "<br>");
           }                                       
               addtwonumber(33,22);
               addtwonumber(3,4);
               addtwonumber(4,5);
               addtwonumber(3,5);
               addtwonumber(11,77);


 DEFAULT PARAMETER
---------------------------------------------------------

                function addtwonumber(c,d,e=0){
                     let num1=c;
                        let num2=d; 
                        let num3=e;
                        let sum=num1+num2+num3;
                        document.write(sum+ "<br>");
           }                                       
               addtwonumber(33,22);
               addtwonumber(3,4);
               addtwonumber(4,5);
               addtwonumber(3,5);
               addtwonumber(11,77);


FUNCATION RETURN
----------------------------------------------------
     function addnumber(a,b){
           let sum=a+b;
           return sum;
        }

       let res=addnumber(1,2)+7;
      document.write(res);

      IIF / ANONYMOUS FUNCATION
-------------------------------------------------------------


 (()=>{
     
        document.write( "i am iff funcation<br>");
      })()


ARROW/ LAMDA FUNCATION
-----------------------------------------------------
    let myfun=(a,b)=>{
                let sum=a+b;
                document.write(sum+"<br>");
           }
   
            myfun(3,4);

ARROW INLINE FUNCATION
-----------------------------------------------------
  let infun=(a,b)=> document.write(a+b+"<br>");
                infun(5,6);






 
                                                                           MODIUL 8 CLASS 1
 --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

PREE RECODET VIDEO
-----------------------------------

1.WINDOW OBJECT
-----------------------------------------
2.JAVASCRIPT NAVIGATOR OBJECT
---------------------------------------
3.JS GEOLOCATION
------------------------------
4.JS COMMON EVENTS
--------------------------------------























WINDOW OBJECT
--------------------------------------------------------------

function ObjAlert(){
alert("This is Alert Box");
}

function ObjConfirm(){
   let result = confirm("This is Confirm Box");
   document.write(result);
}

function ObjPrompt(){
   let result = prompt("This is Prompt Box");
   document.write(result);
}

function Objopen(){
open();
}

function Objclose(){
close();
}


setTimeout (function (){
    alert("This is a delayed alert!");
}, 10000);



JAVASCRIPT NAVIGATOR OBJECT
--------------------------------------------


var appCodeName=navigator.appCodeName;
var appName=navigator.appName;
var appVersion=navigator.appVersion;
var cookieEnabled=navigator.cookieEnabled;
var language=navigator.language;
var userAgent=navigator.userAgent;
var platform=navigator.platform;


document.write("appCodeName: " + appCodeName + "<br>");
document.write("appName: " + appName + "<br>"); 
document.write("appVersion: " + appVersion + "<br>");
document.write("cookieEnabled: " + cookieEnabled + "<br>");
document.write("language: " + language + "<br>");
document.write("userAgent: " + userAgent + "<br>");
document.write("platform: " + platform + "<br>");  

JS GEOLOCATION
-------------------------------------------
   navigator.geolocation.getCurrentPosition(function(position){
                            var altitude = position.coords.altitude;
                            var latitude = position.coords.latitude;
                            var longitude = position.coords.longitude;
                            var speed = position.coords.speed;

                            document.write("Latitude: " + latitude + "<br>");
                            document.write("Longitude: " + longitude + "<br>");
                            document.write("Speed: " + speed + "<br>");
                            document.write("Altitude: " + altitude + "<br>");

                          })
                                              JS COMMON EVENTS
 ------------------------------------------------------------------------------------------------------------


                            function myevent(msg){
                                console.log(msg)
                            }

<button onclick="myevent('click hoyese')">click hoyese</button>
<button onchange="myevent('change hoyese')">change hoyese</button>
<button onmouseover="myevent('mouseover hoyese')">mouseover hoyese</button>
<button onmousemove="myevent('mousemove hoyese')">mousemove hoyese</button>


             DOCUMENT OBJECT
----------------------------------------------------------------



   <h1 id="myid"></h1>
<h2 class="myclass"></h2>
<h2 class="myclass"></h2>
<h2 class="myclass"></h2>
<h2 class="myclass"></h2>

<h3 name="myname"></h3>
<h3 name="myname"></h3>
<h3 name="myname"></h3>
<h3 name="myname"></h3>
<h3 name="myname"></h3>





                var elementById = document.getElementById("myid");
            elementById.innerHTML ="This is heading 1";

            var elementbyclass =document.getElementsByClassName("myclass");

            elementbyclass[2].innerHTML = "This is heading 2";

            var elementbyname = document.getElementsByName("myname");
            elementbyname[3].innerHTML = "This is heading 3";

            var elementbytagname = document.getElementsByTagName("h2");
            elementbytagname[1].innerHTML = "This is heading 4";







<button onclick="demo()">Demo</button>




              function demo(){
        let w=window.open();

        w.document.open();
        w.document.write("hello new window");
        w.document.close();
         
      }