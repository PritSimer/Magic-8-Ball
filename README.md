# Magic-8-Ball
Codecademy Javascript Beginners Practice Project
let userName = 'Sim';
let randomNumber = Math.floor(Math.random()*8);

let eightBall = '';

let userQuestion = '"Will it rain tomorrow?"'

userName ? console.log(`Hello, ${userName}.`) : console.log(`Hello!`);

console.log(`${userName}, you have asked Magic Eight Ball ${userQuestion}.`)

/*randomNumber === 0 ? eightBall = randomNumber : eightBall = randomNumber;
*/
if (randomNumber === 0) {
  eightBall= randomNumber;
console.log(+eightBall+'.'+'It is certain');
} else if (randomNumber === 1) {
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'It is decidely so')
} else if (randomNumber === 2){
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'Really hazy try again')
} else if (randomNumber === 3){
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'Cannot predict now')
} else if (randomNumber === 4){
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'Do not count on it')
} else if (randomNumber === 5){
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'My sources say no')
} else if (randomNumber === 6){
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'Outlook not so good')
} else if (randomNumber === 7){
  eightBall= randomNumber;
  console.log(+eightBall+'.'+'Signs point to yes')
} else {
  console.log('Error!');
}


/*console.log(eightBall);

switch (randomNumber){

  case 0:
  console.log(`It is certain`);
  break;
  case 1:
  console.log(`It is decidely so`);
  break;
  case 2:
  console.log(`Really hazy try again`);
  break;
  case 3:
  console.log(`Cannot predict now`);
  break;
  case 4:
  console.log(`Do not count on it`)
  break;
  case 5:
  console.log(`My sources say no`)
  break;
  case 6:
  console.log('Outlook not so good');
  break;
  case 7:
  console.log(`Signs point to yes`);
  break;

}
*/
