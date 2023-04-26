# To cover the basics of the useEffect hook, here are some tasks i completed below.

The following exercises should all be performed within the Child component.

console.log the text Render each time the component re-renders
console.log the text Hi when the component mounts
console.log the text My name is {name} and I am {age} years old whenever the name or age changes
Update the document.title to be equal to name whenever the name changes
console.log the text Bye when the component unmounts
Create a timeout that console.logs the text My name is {name} only after there has been a 1 second delay since the last time the name was changed. For example, if I change the name from weather to weath and then to wea without having more than 1 second between each name change the console should log nothing until 1 second after I finishing changing the name to wea and then it will log wea. If instead there as greater than 1 second delay between each change, it should log weath and then wea. Each of those logs would happen exactly 1 second after the name was changed.