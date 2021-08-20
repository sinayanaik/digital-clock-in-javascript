#### what i learned from it
How to automatically run a function in a time interval
```js
setTimeout(functionName, Repeat time in millisecond);
```

#### Work with date and time
```js
 let date = new Date();
    let dayNumber = date.getDay();
    let hour = date.getHours();
    let minute = date.getMinutes();
    let second = date.getSeconds();
    let ampm = hour >= 12 ? 'PM' : 'AM';
    let dayNames = ['SUN', 'MON', 'TUE', 'WED', 'THU', 'FRI', 'SAT'];

    if (hour == 12) {
        hour = '12';
    } else {
        hour = hour % 12;
    }

    hour = hour < 10 ? '0' + hour : hour;
    minute = minute < 10 ? '0' + minute : minute;
    second = second < 10 ? '0' + second : second;
```