# Sokolovskaya Lissa

# My Contact info

* **Phone:** +7 912 747 11 17
* **E-mail:** sokolovskaya_lisa@mail.ru
* **GitHub:** [Mikkumo](https://github.com/Mikkumo) 
* **Telegram** [Mikkumo](https://t.me/Mikkumo)

# About me

I'm 23 years old, I work as equipment repair master. My work is interesting, but monotonous. After working in my company for two years, I quit and tried myself in other areas, but I didn’t stay anywhere because it got boring. A year later, in the fall of 2021, I returned to my old job, but continued to look for interesting job options. Then I stumbled upon and delved into the profession of a front end developer.. and it got me very interested! 
Now my main goal is to get as much knowledge in this area as possible and become a front-end developer **:)**

# Skills

* HTML
* CSS
* Git/GitHub
* Figma
* JavaScript Basics
* VS Code

# Code examples

**Lottery Ticket kata from Codewars:** Given a lottery ticket (ticket), represented by an array of 2-value arrays, you must find out if you've won the jackpot. To do this, you must first count the 'mini-wins' on your ticket. Each subarray has both a string and a number within it. If the character code of any of the characters in the string matches the number, you get a mini win. Note you can only have one mini win per sub array.

Once you have counted all of your mini wins, compare that number to the other input provided (win). If your total is more than or equal to (win), return '*Winner!*'. Else return '*Loser!*'.

```js
function bingo(ticket, win){
  let miniWin = 0
  let ticCode = 0
  for (let i = 0; i < ticket.length; i++) {
    for (let j = 0; j < ticket[i][0].length; j++) {
      ticCode = ticket[i][0][j].charCodeAt()
      if (ticCode === ticket[i][1]) {
        miniWin++ 
        break
      }
    }
  }
  return (miniWin >= win) ? 'Winner!' : 'Loser!'
}
```

# Education



# Languages

* **Russian** - native speaker
* **English** - A2 (B1 in process...)
