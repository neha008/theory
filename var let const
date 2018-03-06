var nameVar = "neha";
nameVar = "shally";//(reassign valid for var)
var nameVar = "hii";//(redefine valid for var )
console.log(nameVar);

let nameLet = "jen";
nameLet = "julie";//(reassign valid for let)
//let nameLet ="bnb";(redefine invalid for let)
console.log(nameLet);


const nameConst = "frank";
//nameConst = "lilly";//(reassign invalid for const )
//const nameConst  ="bnb";(redefine invalid for const)
console.log(nameConst);

function getPetName() {
    var petName = "hal";
    return petName;
}
getPetName();//will return petname  
var petName=getPetName();//will return petname
//console.log(petName);//will not work outside the funtion

function getPetName() {
    let petName = "jjj";
    return petName;
}
getPetName();//will return petname  
//let petName=getPetName();//let variables cannot be redefined 
//console.log(petName);//will not work outside the funtion

function getPetName() {
    const petName = "hal";
    return petName;
}
getPetName();//will return petname 
//const petName=getPetName();//will return petname 
//console.log(petName);//will not work outside the funtion

//block scoping

var fullName = "neha jain";
if(fullName) {
    var firstName = fullName.split(' ')[0];
    console.log(firstName);    
}
console.log(firstName);//will work as var based variable are function scoped


if(fullName) {
    let firstName = fullName.split(' ')[0];
    console.log(firstName);    
}
//console.log(firstName);//will not  work as let based variables are block scoped hich also includes functions


if(fullName) {
   const firstName = fullName.split(' ')[0];
    console.log(firstName);    
}
//console.log(firstName);//will not  work as const based variables are block scoped hich also includes functions

//to solve this problem
let firstName1;//make it undefined outside the block
if(fullName) {
    firstName1 = fullName.split(' ')[0];
    console.log(firstName);    
}
console.log(firstName1);
