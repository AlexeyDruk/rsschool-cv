## Personal information
 1. _Alexey Druk_
 2. _drukaleksej91@gmail.com_

3. _I'm constantly reading something new and trying to make up, there are a couple of projects on github_
_may2021 - august2021_
_assiduity_
_attentive_
_learner_
_learner hardworking_

4. _HTML CSS and JS basis vsCode_

5. let buttonsTwo = [];
  window.onload = function() {
  let buttons = document.getElementsByTagName('button');
   for (var i = 0; i < buttons.length; i++) {
     buttonsTwo.push(buttons[i]);
   }
   function shuffle(buttonsTwo) {
  buttonsTwo.sort(() => Math.random() - 0.5);
};
shuffle(buttonsTwo)
console.log(buttonsTwo);
};
 function arr(){
  let buttons = document.getElementsByTagName('button');
  function shuffle(buttons) {
  buttons.sort(() => Math.random() - 0.5);}
    console.log(buttons);
  shuffle(buttons)
  };
  arr(); 
  function getID(event){
  let a = event.target.id;
  a = document.getElementById(a);
  a.classList.remove('img_none');
  setTimeout(()=>a.classList.add('img_none'),300);
  comparisonClass(a);
};
let c;
let c_classNAme;
function comparisonClass(a) {
  let b = a;
  let b_classNAme = b.className;
  let arr = document.getElementsByClassName(b_classNAme);
  comparison(b,c); 
  if (b_classNAme === c_classNAme && comparison(b,c)) {
  setTimeout(() => alert('Поздравляю,вы нашли одинаковые картинки!'), 500);
  arr[0].classList.add('img_black');
  arr[1].classList.add('img_black');
} else {
  c_classNAme = b_classNAme ;
  c = b
}
};

function comparison(b,c) {
  if (b !== c) {
    return true
  } else {
    console.log('Так нельзя');
  }
};

6. https://github.com/AlexeyDruk/First_project 
   https://github.com/AlexeyDruk/Game

7._Plumbing engineer_ 
  _I was trained in the IT Academy "HTML CSS and JS basis"_

8. _I've been studying English for a couple of months, I can't tell the level._



