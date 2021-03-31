# calculator.js
/**
*calcultor module
*@param {*} first
*@param {*} second
*/

const calculator = class {
   constructor(first, second) {
   this.first = first;
   this.second = second;
}

/** 
* addition opertion
* @param : 'this.first' and 'this.second';
* @return type : number;
* @description: addition of two numbers;
*/
addition =() => {
return this.first + this.second;
}

/**
*subtraction of two numvers
*@param : 'this.first' and 'this.sceond';
*@return type :number;
*@desc : subtraction of two numbers;
*/
subtract = () => {
 return this.first - this.second;
 }
 
 /**
*multiplication of two numbers
*@param : 'this.first' and 'this.sceond';
*@return type :number;
*@desc : multiplication of two numbers;
*/
multify = () => {
return this.first * this.second;
}
/**
*devision of two numvers
*@param : 'this.first' and 'this.sceond';
*@return type :number;
*@desc : subtraction of two numbers;
*/
devision = () => {
 return this.first / this.second;
 }
 
 /**
*find the max of two numvers
*@param : 'this.first' and 'this.sceond';
*@return type :number;
*@desc : return the max values;
*/
findThemxa = () =>{
 if (this.first > this.second) {
  return this.first;
  } else {
   return this.second;
  }
 }
 /**
* find the min values 
*@param : 'this.first' and 'this.sceond';
*@return type :number;
*@desc : return the min values;
*/
findTheMin = () => {
 return this.first > this.second ? this.second :this.first;
}
}
module.exports = {
calculator: calculator
};



 
