# my-firs-pro
 let ttx=`^${"*".repeat(20)}\n|\t  ${"*".repeat(20)} \n|\t  |\n^${"*".repeat(6)}   ${"*".repeat(23)}\n\t  |\t\t\t\t\t\t\t|\n\t  ${"*".repeat(27)}`;
console.log(ttx);
console.log("_".repeat(100));



///////////////////////////////////////////////
//problem 1:
// function rev(val){
   
// return (val.split("").reverse().join(""));
// };
// str=prompt("please enter your string");
// console.log(rev(str));




///////////////////////////////////////////////
//problem 2:
// function factorial(num){
//     n=1;
//     for(i=1;i<=num;i++){
//         n *=i;
//     }
// return n;
// };
// num=prompt("please enter your number");
// console.log(factorial(num));




///////////////////////////////////////////////
//problem 3:
// function prim(num){
//     for (let index = 2; index < num; index++) {
//        if( num%index == 0) {
//             console.log("not prime");
//             return;
//        };
//     };
//     console.log("it is prime");
//     return;
// };
// num=prompt("please enter your number");
// console.log(prim(num));




///////////////////////////////////////////////
///////////////////////////////////////////////
///////////////////////////////////////////////
//problem 4:
// function find(l){
//     console.log(` max = :  ${Math.max(...l)}`);
//     console.log(` min = :  ${Math.min(...l)}`);
// };
// num=prompt("please enter your number");
// console.log(find(num))
///////////////////////////////////////////////
//problem 5:

// let l=[1,3,2];
// function sort1(...arr){
//      return(arr.sort());
// };
// console.log(sort1(...l));






///////////////////////////////////////////////
//problem 6:
// class user{
//     constructor(name=null,age=0,address=null){
//         this.name=name;
//         this.age=age;
//         this.address=address;
//     };
//     modi(name,age,address) {
//         this.name=name||this.name;
//         this.age=age||this.age;
//         this.address=address||this.address;
//     };
//     print(){
//         console.log(this.name);
//         console.log(this.age);
//         console.log(this.address);
//     }
// }
// let obj= new user("shahd",20,"lll");
// obj.print();
// obj.modi("nour");
// obj.print();




///////////////////////////////////////////////
//problem 7:
// function rev(val){
   
//     return (val.split(" ").reverse().join(" "));
//     };
//     str=prompt("please enter your string");
//     console.log(rev(str));




///////////////////////////////////////////////
//problem 8:


// function anagrams(x,y)
// {
//     if(x.length === y.length)
//     {
//             for (let index = 0; index < x.length; index++)
//             {
//                 if(! x.includes(y[index]))
//                 {
//                     console.error(" it's not anagrams");
//                     return;
//                 };
//             }
//             console.log(" it's anagrams");
//     } 
//     else{
//        console.error("length it's not same");
//        }
// };
// x=prompt("please enter your string (1)");
// y=prompt("please enter your string (2)");
// anagrams(x,y);





///////////////////////////////////////////////
//problem 9:   Don't forget the bonus (*_*)

// arr=[1,2,3,4,5,6];
// let f= arr.filter((val)=>{return val%2===0; });
// console.log(f);





///////////////////////////////////////////////
//problem 10:

// function unique(l){
//     let s = new Set(l);
//     return s;
// };
// l=[1,2,3,3];
// console.log(unique(l));





///////////////////////////////////////////////
//problem 11:
// function days(str1,str2){
// date1= new Date(str1);
// date2=new Date(str2);
// avr  = (date1-date2)/1000/60/60/24;
// console.log(avr);
// };
// str1="1 ,10,1999";
// str2="1 ,10,1998";
// days(str1,str2);








///////////////////////////////////////////////
//problem 12:
// let p1= new Promise((s,f)=>{
//     setTimeout(() => {
//      x= prompt("please enter your gpa (1)");
    
//         if(x>3){
//             s("good");
//          }
//          else{
//             f("ahbl");
//          }
//      },3000);
     
// }).then(alert).catch(console.error);


// let p2= new Promise((s,f)=>{
//     setTimeout(() => {
//      x= prompt("please enter your gpa (2)");
    
//         if(x>3){
//             s("good");
//          }
//          else{
//             f("ahbl");
//          }
//      },1000);
     
// }).then(alert).catch(console.error);
////////////////////////////////////////////
//async/await

// async function m(){
//     let p1=await new Promise((s,f)=>{
//         setTimeout(() => {
//          x= prompt("please enter your gpa (1)");
        
//             if(x>3){
//                 s("good");
//              }
//              else{
//                 f("ahbl");
//              }
//          },3000);
         
//     }).then(alert).catch(console.error);
    
    
//     let p2=await new Promise((s,f)=>{
//         setTimeout(() => {
//          x= prompt("please enter your gpa (2)");
        
//             if(x>3){
//                 s("good");
//              }
//              else{
//                 f("ahbl");
//              }
//          },1000);
         
//     }).then(alert).catch(console.error);

// };

// m();






///////////////////////////////////////////////
//problem 13:
// class stack{
// constructor(...l){
//     this.l=l;
// };
//  add(val){
//     this.l.push(val);
//  };
//  delete(){
//     this.l.pop();
//  };
//  print(){
//     console.log(this.l);
//  };
// };
// l=new stack(1,2,3);

// l.add(5)

// l.print();
// l.delete();
// l.print();






///////////////////////////////////////////////
//problem 14:
// class node {
// constructor(data,next=null){
//     this.data=data;
//     this.next=next;
// };
// };
// class stack{
//     constructor()
//     {
//        this.head=null;
//        this.temp=null;
//        this.size=0; 
//     }
//     push(data)
//     {
//        this.temp=this.head;
//        this.head = new node(data, this.head);
//        this.size++;
//     };
//     pop(){
//         this.head=this.temp;
//         this.size--; 
//     }
    
// }


// l=new stack();

// l.push(1);
// l.push(2);
// l.push(3);
// l.pop();
// console.log(l);
////////////////////////////////////// 
//Another solution


// class node {
//     constructor(data,next=null){
//         this.data=data;
//         this.next=next;
//     };
//     };
//     class stack{
//         constructor()
//         {
//            this.head=null;
        
//            this.size=0; 
//         }
//         push(data)
//         {
           
           
//            let n = new node(data);

//            n.next=this.head;
//            this.head= n;
//            this.size++;
//         };
//         pop(){
//             this.head=this.head.next;
//             this.size--; 
//         }
        
//     }
//     l=new stack();

// l.push(1);
// l.push(2);
// l.push(3);
// l.pop();
//console.log(l);
    
///////////////////////////////////////////////
//problem 15:
// l=5;//5*4*3*2
// function rec(l)
// {
    
//   if(l===1){
//     return 1;
//   }
//   else{
//     return (l*rec(l-1));
//   }

// };



// console.log(rec(l));


///////////////////////////////////////////////
//problem 16:

// function sum(n){
//     return print(n+5);
// };
// function print(n){
//     console.log(`number = ${n}`);
// };

// sum(5);








///////////////////////////////////////////////
//problem 17:
// let p1= new Promise((s,f)=>{
//         setTimeout(() => {
//          x= prompt("please enter your gpa (1)");
        
//             if(x>3){
//                 s("good");
//              }
//              else{
//                 f("ahbl");
//              }
//          },3000);
         
//     })
    
    
//     let p2= new Promise((s,f)=>{
//         setTimeout(() => {
//          x= prompt("please enter your gpa (2)");
        
//             if(x>3){
//                 s("good");
//              }
//              else{
//                 f("ahbl");
//              }
//          },1000);
         
//     });
//     Promise.all([p1,p2]).then(alert).catch(console.error);




///////////////////////////////////////////////
//problem 18;
// let l1="ma5louf.org";//tm
// let l2="https://ma5louf.org";//tm
// let l3="http://ma5louf.com";//tm
// let l4="https://www.ma5louf.org";//tm
// let l5="https://www.ma5louf.org:8080/art.php?id=1111cat=top";
// let l= /(https?:\/\/)?(www.)?ma5louf.(com|org)(:8080\/art.php\?id=1111cat=top)?/ig;
// console.log(l1.match(l));
// console.log(l2.match(l));
// console.log(l3.match(l));
// console.log(l4.match(l));
// console.log(l5.match(l));

