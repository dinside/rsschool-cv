<h1>Resume</h1>

Kirill Safonov

Му contacts: phone +998 97 444-09-27 / telegram: @xinickkxn

<h2>About me:</h2>
I was born in Uzbekistan, the city of Tashkent. Im graduated from high school and entered the College of Information Technology, the Faculty of Computer and software engineering.
My programming path began with studying python, because he taught at my college. After college, I started getting into web development. I made a full-fledged website and uploaded it to Github, at that moment my joy knew no bounds. But I still didn't have enough experience to get a job as a web developer. Therefore, at that time, working in the Internet provider Comnet, from the position of coordinator, I moved to the position of Digital marketer, in order to be in the IT department to gain experience from developers. Since December 2020, I have been entrusted with the development of the comnet.uz website since that time, I have been doing edits and upgrades on the site. In my free time after work, I devote time to learning new material, to improve my programming skills. 

<h3>Skills:</h3>

- [x] HTML
- [x] CSS
- [ ] JS
- [x] Photoshop / Figma

```c
function formatDuration(seconds) {
    if (seconds === 0) {
        return 'now';
    }
    var numYears = Math.floor(seconds / (86400 * 365));
    var numDays = Math.floor(seconds % (86400 * 365) / 86400);
    var numHours = Math.floor(((seconds % (86400 * 365)) % 86400) / 3600);
    var numMinutes = Math.floor((((seconds % (86400 * 365)) % 86400) % 3600) / 60);
    var numSeconds = (((seconds % (86400 * 365)) % 86400) % 3600) % 60;

    var secondsFun = function () {
        return (numSeconds ? (((seconds > 60) ? ' and ' + numSeconds + " second" : +numSeconds + " second") + (numSeconds === 1 ? '' : 's')) : '');
    };

    var minutesFun = function () {
        if (numSeconds === 0 && numDays !== 0) {
            return 'and ' + (numMinutes ? numMinutes + " minute" + (numMinutes === 1 ? '' : 's') : '');
        }
        return (numMinutes ? numMinutes + " minute" + (numMinutes === 1 ? '' : 's') : '');
    };

    var hoursFun = function () {
        if (minutesFun().charAt(0) === 'a') {
            return (numHours ? numHours + " hour" + (numHours === 1 ? ' ' : 's ') : '');
        }
        if (numSeconds === 0 && numMinutes === 0) {
            return (numHours ? numHours + " hour" + (numHours === 1 ? '' : 's') : '');
        }

        return (numHours ? numHours + " hour" + (numHours === 1 ? ', ' : 's, ') : '');
    };

    var daysFun = function () {
        return (numDays ? numDays + " day" + (numDays === 1 ? ', ' : 's, ') : '');
    };

    var yearsFun = function () {
        return (numYears ? numYears + " year" + (numYears === 1 ? ', ' : 's, ') : '');
    };

    return yearsFun() + daysFun() + hoursFun() + minutesFun() + secondsFun();
}



console.log(formatDuration(3600));
```


<h4>Experience at DEV:</h4>

> OOO "IPLUS" TM COMNET - Junior Frontend Developer  12020 - to this day

<h5>Educattion:</h5>
  
> Secondary special education at college MKKT in Tashkent. Faculties Computer and software engineering

<h6>English:</h6>

> A2+