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