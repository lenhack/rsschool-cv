# Olena Koppalova

### Junior Frontend Developer

---

![Olena Koppalova](/images/myPhoto.jpg)

---

## Contact information:

**Phone:** +380 96 46 55 153

**E-mail:** lenhack1@gmail.com

**Telegram:** @YelenaDK

**LinkedIn:** (http://linkedin.com/in/елена-коппалова-8538a91b6)

---

## About myself:

I have dreamt of becoming a web developer for a long time. I started with learning Java on "Java Rush" and Python on "Stepik" in 2020. Being a bit disoriented about where to start, I took advice to learn QA before programming, so in 2021 I graduated from an Online University TOMMY as a QA. With this experience on my hands, I became reassured in my desire to be a developer. So, I made a final decision to study Front-End Development in RS School. I have graduated from Stage 0 successfully in February 2022. Unfortunately I had to stop learning because of war in Ukraine.  However I decided to continue learning. I can surely say that I enjoy doing various tasks, I love the feeling of satisfaction I get from a completed piece of work and wish to fulfill my dream of practicing web development.

---

## Skills and Proficiency:

- HTML5, CSS3;
- JavaScript;
- Python Basics;
- Java Basics;
- C Basics;
- Git, GitHub;
- VS Code;
- Figma;
- Adobe Photoshop, Corel DRAW

---

## Code example:

- **JavaScript**

  _This function formats a duration, given as a number of seconds, in a human-friendly way._

```JavaScript
function formatDuration (seconds) {

if(seconds === 0) return 'now'

let deviderForYears = 60 * 60 * 24 * 365;
let deviderForDays = 60 * 60 * 24;
let deviderForHours = 60 * 60;
let deviderForMinutes = 60;
let remainder = 0;

let yearsNumber = Math.floor(seconds / deviderForYears);
remainder = seconds % deviderForYears;
let daysNumber = Math.floor(remainder / deviderForDays);
remainder = remainder % deviderForDays;
let hoursNumber = Math.floor(remainder / deviderForHours);
remainder = remainder % deviderForHours;
let minutesNumber = Math.floor(remainder / deviderForMinutes);
remainder = remainder % deviderForMinutes;
let secondsNumber = remainder;

let secondsAnswer = '';
let minutesAnswer = '';
let hoursAnswer = '';
let daysAnswer = '';
let yearsAnswer = '';

if(secondsNumber === 1){
    secondsAnswer = `${secondsNumber} second`;
} else if(secondsNumber > 1){
    secondsAnswer = `${secondsNumber} seconds`;
}

if(minutesNumber === 1){
    minutesAnswer = `${minutesNumber} minute`;
} else if(minutesNumber > 1){
    minutesAnswer = `${minutesNumber} minutes`;
}

if(hoursNumber === 1){
    hoursAnswer = `${hoursNumber} hour`;
} else if(hoursNumber > 1){
    hoursAnswer = `${hoursNumber} hours`;
}

if(daysNumber === 1){
    daysAnswer = `${daysNumber} day`;
} else if(daysNumber > 1){
    daysAnswer = `${daysNumber} days`;
}

if(yearsNumber === 1){
    yearsAnswer = `${yearsNumber} year`;
} else if(yearsNumber > 1){
    yearsAnswer = `${yearsNumber} years`;
}

const readableTime = [yearsAnswer, daysAnswer, hoursAnswer, minutesAnswer, secondsAnswer];
const newReadableTime = [];

for(let i = 0; i < readableTime.length; i++){
    if(readableTime[i] != ''){
        newReadableTime.push(readableTime[i])
    }
}
return newReadableTime.join(', ').replace(/,[^,]+$/, ' and ' + newReadableTime[newReadableTime.length - 1]);
}
```

- **C**

  _This function converts the string argument str to an integer (int type) and returns it._

```C
char* ft_itoa(int n){
    int t = n;
    int len_num = 0;
    while(t/=10){
        len_num++;
    }
    len_num++;

    char* str = (char*)malloc(len_num +1);
    int i = 0;

    if(n<0){
        str[0] = '-';
        n *= -1;
        i++;
    }

    while(len_num >= i){
        str[len_num] = (n%10) + '0';
        n/=10;
        len_num--;
    }
    str[ft_strlen(str)] = '\0';
    return str;
}
```

---

## Experience:

### FOUNDER AND LECTURER AT COMPUTER COMPETENCE CENTER “STREAM”

##### *SEPTEMBER 2018 — JULY 2020*

+ Teaching the basics of working with computer programs
+ Teaching the basics of programming

### IT ASSISTANT IN COMPUTER REPAIR SERVICE CENTER

##### *NOVEMBER 2011 — JUNE 2018*

+ Installing and configuring software
+ Repairing computers, laptops

### PARENTAL LEAVE AND A PART-TIME JOB AS A CONTENT MANAGER AT THE INTERNET PROVIDER “X-NET”

##### *NOVEMBER 2008 – NOVEMBER 2011*

+ Populating the content of the ISP's website

### ADVERTISING DESIGNER AT ADVERTISING AGENCY "LEGION"

##### *OCTOBER 2007 – NOVEMBER 2008*

+ Designing of posters, large format advertisements, flyers, etc.

---

## Projects:

- [https://tic-tac-toe-lenhack.netlify.app/](https://tic-tac-toe-lenhack.netlify.app/)

- [https://eco-sounds-lenhack.netlify.app/](https://eco-sounds-lenhack.netlify.app/)

- [https://image-gallery-lenhack.netlify.app/](https://image-gallery-lenhack.netlify.app/)

- [https://portfolio-part3-lenhack.netlify.app/](https://portfolio-part3-lenhack.netlify.app/)

---

## Courses:

- RS Schools Course «JavaScript/Front-end. Stage 0»

- Online University TOMMY "Тестувальник програмного
  забезпечення (QC / QA)" [Online University TOMMY](https://www.tommyuniver.com)

---

## Languages:

- English (in the range of B1 INTERMEDIATE to B2 UPPER INTERMEDIATE);
- Russian (Native);
- Ukrainian (Native);
- German (B1)
