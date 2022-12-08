# Valeriia Khodzhaeva

****

## My Contact Info
* Address: Krasnodar, Russia
* Telegram: +79181826851
* E-mail: cactusxd79@gmail.com
* GitHub:  [ValHoge](https://github.com/ValHoge)

****

### About me 
I am a junior front-end developer. I make landings and small multi-page sites, I also have experience in web application development (https://xn--80ahacbc6bzajmo6j.xn--80asehdb/).


I am curious and prone to self-learning. At one time I studied design, traffic arbitrage and SMM.


I drew all my projects in Figma. At the moment, I don’t actively practice design, but I try to follow the trends. 

****

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

****

#### My experience
1. [predsedatel online](https://xn--80ahacbc6bzajmo6j.xn--80asehdb/)

*Responsibilities:*
+ website design;
+ site layout;
+ application design;
+ layout of the browser version of the application;
+ teamwork with backend developers;


2. [glory store](https://glorystore.ru/)

*Responsibilities:*
+ prototyping of the main page of the online store, product cards;
+ layout of the main page, product card, template for useful articles;
+ execution of administrative orders;
+ assistance in business organization;
+ filling out cards in 1c and transferring this data to bitrix;
+ image processing for product cards.

****

#### Courses:
* HTML and CSS [glo.academy](https://glo.academy/web-developer/) (completed)
* JS [glo.academy](https://glo-academy.ru/jscript/) (in proсess)
* JavaScript Manual on learnjavascript.ru (in proсess)
* lessons from youtube
* [RS Schools Course «JavaScript/Front-end. Stage 0»](https://rs.school/) (in proсess)

****

#### Languages

* English - pre intermediate (A2)
* Russian - Native