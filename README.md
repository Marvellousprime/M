
function toggleThemeSelector() {
      var themeSelector = document.getElementById("themeSelector");
      themeSelector.style.display = (themeSelector.style.display === "none" || themeSelector.style.display === "") ? "block" : "none";
    }
let themeOption;
    const themes = {
        changeTheme:function(){
const themesDisplay =  document.querySelectorAll('.theme') 

for( themeDisplay of themesDisplay){
themeDisplay.onclick = function (){
    themeOption = this.innerHTML;
    console.log(themeOption)
    condition()
    SaveData()
  }  
  
}



  }
    }
    themes.changeTheme()
/*#8B00FF (Dark Pink)
#FFC0CB (Pink)*/
 function condition(){
console.log(themeOption)
const body = document.body 
const balance = document.getElementById('balance')
const Body = document.getElementById('body')
const play = document.getElementById('play')
const toggleTheme = document.getElementById('toggleTheme')
const gamedisplay = document.getElementById('gamedisplay')
const h = document.getElementById('h')
const tools = document.getElementById('tools')
const toolsButton = document.querySelectorAll('#tools button')
const newP  = document.getElementById('MessageParagraph')
const themeSelector = document.getElementById('themeSelector')
switch (themeOption) {
 case 'Light blue':
 themeOption = 'Light blue'
 body.style.background = '#EDF0FF';
balance.style.color = 'blue';
 balance.style.background = '#7C9BF7';
 balance.style.boxShadow = '0 5px 7px #B4BEFF';
 Body.style.background = 'royalblue';
 play.style.color = 'white';
 play.style.background = '#A8B7FF';
 play.style.boxShadow = '0px 5px 5px #053EE7DE'
 toggleTheme.style.boxShadow = '0px 5px 5px #053EE7DE'
 toggleTheme.style.color = 'white';
 toggleTheme.style.background = '#A8B7FF';
 gamedisplay.style.background = '';
 h.style.color = 'black';
 tools.style.background= 'white';
toolsButton.forEach (function (element,index) {
    element.style.background = ' #A8B7FF'
    element.style.boxShadow = '0px 5px 5px #053EE7DE'
    
})
newP.style.background = 'white'
themeSelector.style.background = 'white'
     break;
  case   'Dark blue':
  themeOption = 'Dark blue'
   body.style.background = '#101369';
balance.style.color = 'black';
 balance.style.background = '#2126d3';
 balance.style.boxShadow = '0 5px 7px #0026d3';
 Body.style.background = 'royalblue';
 play.style.color = 'white';
  play.style.boxShadow = '0px 5px 5px #053EE7DE'
 toggleTheme.style.boxShadow = '0px 5px 5px #053EE7DE'
 play.style.background = '#4740ffc8';
 toggleTheme.style.color = 'white';
 toggleTheme.style.background = '#4740ffc8';
 gamedisplay.style.background = '#1f23be';
 h.style.color = '#061f25';
 tools.style.background= '#0c219a';
toolsButton.forEach (function (element,index) {
    element.style.background = 'blue'
    element.style.boxShadow = '0px 5px 5px #053EE7DE'
    
})
newP.style.background = 'royalblue'
themeSelector.style.background = 'royalblue'
break;
case 'Dark green':
  body.style.background = '#19a15f9f';
balance.style.color = 'black';
 balance.style.background = '#19a15fd2';
 balance.style.boxShadow = '0 5px 7px #35a17ad2';
 Body.style.background = '#19a15fd2';
 play.style.color = 'white';
  play.style.boxShadow = 'none'
 toggleTheme.style.boxShadow = 'none'
 play.style.background = '#41a135d2';
 toggleTheme.style.color = 'white';
 toggleTheme.style.background = '#41a135d2';
 gamedisplay.style.background = '#19a15fd2';
 h.style.color = 'white';
 tools.style.background= '#003705f6';
toolsButton.forEach (function (element,index) {
    element.style.background = '#0e552be2'
    element.style.boxShadow = '0px 2px 2px #28702df6 '
    newP.style.background = '#19a15fd2'
})
themeSelector.style.background = '#19a15fd2'
break;
case 'Pink':
  body.style.background = '#FFC0CB';
balance.style.color = 'white';
 balance.style.background = '#623961';
 balance.style.boxShadow = '0 5px 7px #FFA8C1';
 Body.style.background = '#623961';
 play.style.color = 'white';
  play.style.boxShadow = '0 1px 1px #c874c5da'
 toggleTheme.style.boxShadow = '0 1px 1px #c874c5da'
 play.style.background = '#995997';
 toggleTheme.style.color = 'white';
 toggleTheme.style.background = '#995997';
 gamedisplay.style.background = '#623961';
 h.style.color = 'white';
 tools.style.background= '#FFC0CB';
toolsButton.forEach (function (element,index) {
    element.style.background = '#742288da'
    element.style.boxShadow = '0px 2px 2px #b534d5da '
})
 newP.style.background = 'red'
 themeSelector.style.background = '#ffc0cb'
break;
break;
case 'Random':
var Color = new NewColor
console.log(Color.generateColor(8))
console.log(Color.generateColor(6))
 body.style.background = Color.generateColor(8);
balance.style.color = Color.generateColor(6);;
 balance.style.background = Color.generateColor(6);
 balance.style.boxShadow = '0 5px 7px' +''+Color.generateColor(6);
 Body.style.background = Color.generateColor(6);
 
  play.style.boxShadow = '0 1px 1px '+Color.generateColor(6);
 toggleTheme.style.boxShadow = 'none'
 Corlex =  Color.generateColor(6);
 Colorx = Color.generateColor(6)

 toggleTheme.style.color = Colorx;
 toggleTheme.style.background =Corlex; ;
 play.style.color = Colorx;
  play.style.background = Corlex;
 gamedisplay.style.background = Color.generateColor(6);
 h.style.color = Color.generateColor(6);
 tools.style.background= Color.generateColor(6);
toolsButton.forEach (function (element,index) {
    element.style.background = Color.generateColor(6)
    element.style.boxShadow = '0px 2px 2px  ' +Color.generateColor(6)
    console.log(themeOption +'4444455')
})
 newP.style.background  = Color.generateColor(6);
 themeSelector.style.background = Color.generateColor(6);

break;
}

}


 function claimFirstReward() {
       balance += Amount
       document.getElementById('balanceData').textContent =balance + '$'
       bodyElement.style.display = 'none'
   }
function NewpopUpMessage(message,Amount){
   let bodyElement = document.getElementById('MessageParagraph')
   bodyElement.style.display = 'block'
   bodyElement.innerHTML = '<div>'+message+'</div>'
  var claimButton = document.createElement('button')
  claimButton.textContent = 'Claim'
  document.getElementById('MessageParagraph').appendChild(claimButton)
  claimButton.onclick = function () {
      balance += Amount
       document.getElementById('balanceData').textContent ='$'+balance 
       bodyElement.style.display = 'none'
let newTransationDetail = new TransactionClass
 newTransationDetail.updateDetail(Amount,'c')
 transationDetails.push(newTransationDetail)
 resetTransationBox()
  }
}
//class
class NewColor {
  constructor() {
    this.color = "#"
    this.combination = [0,1,2,3,4,5,6,7,8,9,'A','B','C','D','E','F']
  }
  generateColor (length){
    this.color = '#'
    for (var i = 0; i < length; i++) {
let randomIndex = Math.floor(Math.random() * 16 ) 
this.color += this.combination[randomIndex]
    }
    return this.color
  }
  
}
class TransactionClass {
    constructor(){
this.Data = {}        
    }
updateDetail(amount,type){
  this.Data = {
    amount:amount,
    type:type
  }
  }
}

let resetTransationBox = function(){
    document.getElementById('transationlist').innerHTML = ''
    transationDetails.forEach(function (me){
  Amount = me.Data.amount
  type = me.Data.type
  console.log(Amount,type)
var p =   document.createElement('li')
if (type = 'c'){
    p.innerHTML = 'Your account has been credited with '+ '$' +Amount 
}else{
    p.innerHTML = 'Your account has been debited with '+ '$' +Amount
}

document.getElementById('transationlist').appendChild(p)
})
}
//document.getElementById('MessageParagraph').textContent = '67888&&'
//define all variable

var interval;

const playButton = document.getElementById('play')
playButton.addEventListener('click',playButtonClicked)

function playButtonClicked() {
MessageNotice = document.getElementById('promptMsg')
MessageNotice.style.display =(MessageNotice.style.display === "none" || MessageNotice.style.display === "") ? "block" : "none";
  if (balance === 20) {
     MessageNotice.innerHTML = 'sorry you do not have enough balance, you will have to mine money till you have a balance of $20'
    var cancelBtn = document.createElement('button')
    cancelBtn.textContent = 'x'
cancelBtn.onclick = function () {
MessageNotice.style.display =(MessageNotice.style.display === "none" || MessageNotice.style.display === "") ? "block" : "none";
  
}
    var mineBtn = document.createElement('button')
    mineBtn.textContent = 'Mine'
    MessageNotice.appendChild(cancelBtn)
    MessageNotice.appendChild(mineBtn)
    mineBtn.onclick = function() {
clearInterval(interval)
       interval = setInterval(function() {
        balance += 0.1
        balance = balance.toFixed(2);
        // convert to number
        balance = +balance + +0
        document.getElementById('balanceData').textContent = '$' + balance
        console.log(balance)
        if (balance === 30) {

clearInterval(interval)
playButtonClicked() 
        }
      }, 250)


    }
  } else {
MessageNotice = document.getElementById('promptMsg')
    MessageNotice.innerHTML = `it\'s time pls select what u want to do 
    <div style="color:white;">Quick cash</div>
    <div style="color:white" onclick="placeBet()">Bet<div>
    `
  
  }

}
function placeBet() {
  var text = document.createElement('p')
  text.textContent = 'please select the amount you want to bet in'
document.getElementById('promptMsg').appendChild(text)
let Suggestions = [5,10,50,100,150,200,500,1000,2000,5000]
Suggestions.forEach(
  function (me) {
if (balance > me){
  let buttonX = document.createElement('button')
  buttonX.className = 'theme'
  buttonX.onclick = function () {
  var GamingRatio = ['50/50','70/30','80/20']
  var rewardPerRatio = [1,5,3,5]
  var text = document.createElement('p')
text.textContent = 'Pls select your odds 50/50, 70/30, 80/20  '
  document.getElementById('promptMsg').appendChild(text)
  }
  buttonX.textContent = me
  
document.getElementById('promptMsg').appendChild(buttonX)
}
  })
}










let transationDetails = []
let balance = 0
 let data = undefined
let storedData = localStorage.getItem('key')
console.log(storedData)
if(storedData){
 storedData = JSON.parse(storedData);
themeOption = storedData['themeOption']
balance = storedData['balance']
transationDetails = storedData['transationDetails']
console.log(transationDetails,transationDetails)
document.getElementById('balanceData').textContent = '$'+balance
console.log('themeOption is ' + themeOption)
//themeOption = 'Pink'
resetTransationBox()
    condition()
}else{
    NewpopUpMessage('Welcome to this game your price is $20',20)
}


let  Data = {
        
        balance:balance,
        themeOption:themeOption,
        transationDetails:transationDetails
    }
function SaveData(){
     Data = {
        
        balance:balance,
        themeOption:themeOption,
        transationDetails:transationDetails
    }
    
var sterilizedData =  JSON.stringify(Data)
localStorage.setItem('key',sterilizedData)
}
function MoveToSupport() {
SaveData()
console.log(themeOption)
    window.location = 'support.html'
}
function   MoveToHistory() {
SaveData()
    window.location = 'history.html'
}
function   MoveToDashBoard() {
SaveData()
    window.location = 'file.html'
}
function updateTransation() {
    
}
