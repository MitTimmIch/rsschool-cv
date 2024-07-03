![Tim](/rsschool-cv/avatar.png)
# Timur Umarov

 ## Contacts 
 * *Email:* umaroffteymur@yandex.ru
 * *Telegtam:* https://t.me/Tim_mit_mit
 * *Discord:* timur_umar

 ## Language
 * English - A2(B1)

 ## Education 
 Rostov State Conservatory named after S.V. Rachmaninov 2018-2023

 ## Code example 
 ```javascript
 "use strict"

function removeVowelLetters() {
    let text = document.getElementById("page__text-input").value;
    console.log(text);
    const vowelAlphabet = 'аеёоиуэюыя';
    let newText = '';
    for (let i = 0; i < text.length; i++){
        if (!vowelAlphabet.includes(text[i].toLowerCase())){
            newText +=text[i]
        }
    }
    return document.getElementById("result").innerHTML = `Результат: ${newText}`;
}
``` 
## About me 
I'm just learning how to design. Interested in web, because it is fashionable stylish youthful. I aim to become a junior developer in a year.