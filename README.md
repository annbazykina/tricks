# tricks

const RGB = Math.floor(Math.random() * 255);

Write a function called `countOccurrences()` that takes in a string and a character and returns the number of occurrences of that character in the string.
const countOccurrences = (str, char) => str.split(char).length - 1;
