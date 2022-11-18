# DemoAngularFirstProject
// let a : number =9,b=10;
// if(a>b){
//     console.log("a is greater");
// }
// else
// {
//     console.log("b is greater");
// }
// for(let i=0;i<4;i++)
// {
//     console.log("Number is-:"+i);
// }
// let arrayM=[10,20,30,40,50];
//   //two mejor type of loop is used in TS for in and for of loop
//   // for of give u value but for in always give you index
//   for(var val in arrayM){
//     console.log(val);
//   }
  //while loop is same as other language
  //functionn in ts
  function meet()
  {
    return "HELLO"
  }
  
   function meeT(greeting:string,name:string):string// if we want to return a string then we can specify like this
   //and if we are not returning string then it will give error same way we cajn return int and any any typ\e

  {
    return greeting + ' ' + name + '.'
  }
  meet()
  meeT("Mishra","Nitish")
  //interface in ts 
  interface MyUser
  {
    //methods//properties
    userId?:number;//questionnmark means this property is optional
  }
//classes in ts
class Emp implements MyUser{
    name :string;
    userId?:number;
    constructor(name: string,userId: number)
    {
        this.name=name;
        this.userId=userId;
    }
    ShopeMe()
    {
        console.log("Heyyy");
    }
}

//Decorates is TRypeScript VVVVVV-IMP
//private,public,costructor(),\
//@canfly---decorater syntax
