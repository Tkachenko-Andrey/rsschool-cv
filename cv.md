# Andrey Tkachenko 
## Contacts:
+ **Email**   andrew.n.tkachenko@gmail.com
+ **Phone** +79967047747
+ **Telegram** https://t.me/n_e_k_k_i
+ **Github** @Tkachenko-Andrey
***
## About me
My name is Andrey, I'm a webflow developer with 3 years of experience.

He came to development from web design and worked with general studios and agencies such as Clay, Uprock, Pinkman (Method Zero), Cedro, Cloudmill, Accuraten, HTML Academy, etc., in total, independently launched more than 40 projects varying degrees of complexity, from simple landings and corporate sites to promo sites with animations and interaction logic
**https://andrey-tkachenko.webflow.io/ - collected some works here**
I work with BEM
I prefer to typeset in rem for better adaptability
I use swiper in my work. js, a bit of gsap, if necessary I can add locomotive js, but lenis scroll as smooth scroll is more flexible and loads pages less.
I work with lotti files and integrations such as zapier, make, mailchimp familiar with the features of cross-browser layout not afraid of difficult tasks I like to learn and use something new in my work I take criticism calmly and I'm not afraid to talk about what I don't know
***

## Skils
+ **Webflow**
+ HTML/CSS
+ BEM
+ GSAP
+ Zapier, Make
+ Locomotive scroll, Lenis scroll, Swiper JS
***
## Code example 
```
let currentTime = new Date();
let timeValue = new Intl.DateTimeFormat('en-US', {   hour: 'numeric',  timeZone: 'America/Los_Angeles' }).format(currentTime);

const heading = document.querySelector('#radio-heading');
const radioFour = document.querySelector('#radio-four');
const radioSix = document.querySelector('#radio-six');
const twoDaysAfter = document.querySelector('#two-days-after');

if (timeValue === '5 PM' || '6 PM' ) {
    radioFour.style.display = 'flex';
     twoDaysAfter.style.display = 'none';
    console.log("time 16")
} else {radioFour.style.display = 'none';
	twoDaysAfter.style.display = 'flex';
};

 if (timeValue === "7 PM" || "8 PM" || "9 PM" || "10 PM" || "11 PM") {
	radioSix.style.display = 'flex';
    heading.style.display = 'flex';
    radioFour.style.display = 'flex';
    twoDaysAfter.style.display = 'none';
 } else {
 	radioSix.style.display = 'none';
    heading.style.display = 'none';
    radioFour.style.display = 'none';
    twoDaysAfter.style.display = 'flex';
    }
console.log(timeValue);

const today = document.querySelector('.today-date');
const tomorrow = document.querySelector('.tomorrow-date');
const afterTomorrow = document.querySelector('.aftertomorrow-date');
const afterAfterTomorrow = document.querySelector('.two-days-aftertomorrow-date');

// get the day and months
const month = ["January","February","March","April","May","June","July","August","September","October","November","December"];
// get the current date
const d = new Date();
let newDate = month[d.getMonth()]+' '+d.getDate();
let todayDayOfMonth = d.getDate();
let todayMonth = d.getMonth() + 1;
let todayYear = d.getFullYear();
let todayExact = `${todayDayOfMonth}/${todayMonth}/${todayYear}`

const nextDay = new Date();
nextDay.setDate(nextDay.getDate() + 1);
let tommorrowDate = month[nextDay.getMonth()]+' '+nextDay.getDate();
let tommorrowDayOfMonth = nextDay.getDate();
let tommorrowMonth = nextDay.getMonth() + 1;
let tommorrowYear = nextDay.getFullYear();
let tommorrowExact = `${tommorrowDayOfMonth}/${tommorrowMonth}/${tommorrowYear}`

const afterDay = new Date();
afterDay.setDate(afterDay.getDate() + 2);
let afterTommorrowDate = month[afterDay.getMonth()]+' '+afterDay.getDate();
let afterTommorrowDayOfMonth = afterDay.getDate();
let afterTommorrowMonth = afterDay.getMonth() + 1;
let afterTommorrowYear = afterDay.getFullYear();
let afterTommorrowExact = `${afterTommorrowDayOfMonth}/${afterTommorrowMonth}/${afterTommorrowYear}`

const afterAfterDay = new Date();
afterAfterDay.setDate(afterAfterDay.getDate() + 3);
let afterAfterTommorrowDate = month[afterAfterDay.getMonth()]+' '+afterAfterDay.getDate();
let afterAfterTommorrowDayOfMonth = afterAfterDay.getDate();
let afterAfterTommorrowMonth = afterAfterDay.getMonth() + 1;
let afterAfterTommorrowYear = afterAfterDay.getFullYear();
let afterAfterTommorrowExact = `${afterAfterTommorrowDayOfMonth}/${afterAfterTommorrowMonth}/${afterAfterTommorrowYear}`

today.textContent = newDate;
tomorrow.textContent = tommorrowDate;
afterTomorrow.textContent = afterTommorrowDate;
afterAfterTomorrow.textContent = afterAfterTommorrowDate;
```

***
## Experience

**Middle+ Webflow developer** (3 years)
+ Uprock Agency
+ Method Zero
+ StudyWorld
+ Freelance
***
## Education 
Master of History
***
## Languages
+ Russian
+ English -A2
+ 
