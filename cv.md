# Valeriia Khodzhaeva
*******
## My Contact Info
* Address: Krasnodar, Russia
* Telegram: +79181826851
* E-mail: cactusxd79@gmail.com
* GitHub: ValHoge

***
### About me 
I am a junior front-end developer. I make landings and small multi-page sites, I also have experience in web application development (https://xn--80ahacbc6bzajmo6j.xn--80asehdb/).


I am curious and prone to self-learning. At one time I studied design, traffic arbitrage and SMM.


I drew all my projects in Figma. At the moment, I don’t actively practice design, but I try to follow the trends. 

***
### My skills
* HTML5
* CSS
* Frameworks (Uikit, Bootstrap)
* JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM)
* Version control: Github, Bitbucket
* Gulp, Webpack.
* Figma,Adobe Photoshop, Illustrator
* Google ads
****
### Code Examples
```
//timer
    let deadline = '2022-11-29';

    function getTimeremaining(endtime) {
    
        let t = Date.parse(endtime) - Date.parse(new Date()),
            seconds = Math.floor((t/1000)% 60),
            minutes = Math.floor((t/1000/60) % 60),
            hours = Math.floor((t/(1000*60*60))); 
             
            if (seconds < 10) {
                seconds = "0" + seconds;
            }
            if (minutes < 10) {
                minutes = "0" + minutes;
            }
            if (hours < 10) {
                hours = "0" + hours;
            }
            return {
                'total' : t,
                'hours' : hours,
                'minutes': minutes,
                'seconds' : seconds
            };
    }
    
    function setClock(id, endtime) {
				let timer = document.getElementById(id),
				seconds = timer.querySelector('.seconds'),
				minutes = timer.querySelector('.minutes'),
				hours = timer.querySelector('.hours'),
				timeInterval = setInterval(updateClock, 1000);

            function updateClock() {
                let t = getTimeremaining(endtime);
                seconds.textContent = t.seconds;
                minutes.textContent = t.minutes;
                hours.textContent = t.hours;
    
                if (t.total <= 0) {
                    clearInterval(timeInterval);
                }
                
                if (Date.parse(endtime) < Date.parse(new Date())) {
                    seconds.textContent = '00';
                    minutes.textContent = '00';
                    hours.textContent = '00';
                }
            }
    }
    setClock('timer', deadline);
});

``` 
***