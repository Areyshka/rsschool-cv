# Elena Kondel
***

## Contacts:
* Phone: +375 29 588 76 57
* Email: elena.draven@mail.ru
* LinkedIn: [elena-kondel](www.linkedin.com/in/elena-kondel)
* GitHub: [Areyshka](https://github.com/Areyshka)
* Telegram: @areyshka

## About Me:
One of my key qualities is a strong sense of responsibility, sometimes even to the point of being meticulous, as I like to keep everything under control. I am highly adept at working in a team and possess excellent communication skills. My ability to multitask, adapt to different conditions, and maintain self-discipline has been critical in various professional settings. Additionally, I pay great attention to detail and have developed strong critical thinking skills. Moreover, I have a profound passion for learning and continually seek to expand my knowledge and skills.

## Skills:
* HTML
* CSS
* JavaScript
* Git

## Code Example:
```javascript
function treeSum(arr) {
    let sum = 0; 
    for (let i = 0; i < arr.length; i++) {
        if (typeof arr[i] === "number") {
            sum += arr[i];
        } else if (Array.isArray(arr[i])) {
            sum += treeSum(arr[i]);
        }
    }
    return sum;
}
```

