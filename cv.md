# CV for RSSchool

## Miraslau Rabikau - FrontEnd Developer

![Profile image](https://avatars3.githubusercontent.com/u/31839505?s=460&u=5dd0c303295f6980e9897ffdcda2a991ded4d489&v=4)

# Contacts

- *email*: mira2408@mail.ru;
- *VK*: @Mr.Myron;

# Summary

Responsible, executive, creative
I became a front-end developer because I enjoy developing the client side of the web interface. Create animations, adapt for mobile devices. Now I went to RSSchool courses to improve my skill and gain more experience.

# Skills

**Programming languages:** JavaScript Core / jQuery / Ajax, JSON, OOP, MVC
Strong knowledge of HTML5 (semantics, accessibility). CSS3;

# Code examples

```javascript
function calculateMax(array) // finding the maximum element of the array
{
    let max = array[0];
    for(let i = 0; i < array.length; ++i)
    {
        if(array[i] > max)
        {
            max = array[i];
        }
    }
    return max;
}

function calculateMin(array) // finding the minimum element of the array
{
    let min = array[0];
    for(let i = 0; i < array.length; i++)
    {
        if(array[i] < min)
        {
            min = array[i];
        }
    }
    return min;
}

function calculateSum(array) // find the sum of the elements of the array
{
    let sum = 0;
    for(let i = 0; i < array.length; i++)
    {
        sum += array[i];
    }
    return sum;
}

function calculateAverage(array) // find the arithmetic average of all the elements of the array
{
    let sum = 0;

    for(let i = 0; i < array.length; i++)
    {
        sum += array[i];
    }

    return sum / array.length;
}

function getOddInIntervalArray(array) // odd values
{
    let text = '';
    for(let i = 0; i < array.length; i++)
    {
        if(array[i] % 2 != 0)
        {
            text += ' ' + array[i];
        }
    }
    return text;
}

module.exports = 
{
    calculateMax: calculateMax,
    calculateMin: calculateMin,
    calculateSum: calculateSum,
    calculateAverage: calculateAverage,
    getOddInIntervalArray: getOddInIntervalArray
}
```

# Experience

I’ve taken a course on HTML and CSS basics at university and currently studying web development and JavaScript at rs-school.

# Education

graduated from the Gomel State Technical University named after P. About "Sukhoi"
Faculty of Automated and Information Systems;
Department of Information Technologies;
Qualification "Engineer-Programmer".

# English 

My English is a pre intermediate (A2) level