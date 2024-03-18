# tricks

const RGB = Math.floor(Math.random() * 255);

Write a function called `countOccurrences()` that takes in a string and a character and returns the number of occurrences of that character in the string.
const countOccurrences = (str, char) => str.split(char).length - 1;

.truncate-value {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  a {
    display: inline-block;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
}

// .truncate-value a {
// }


// .truncate-value:hover {
//   white-space: normal;
//   overflow: visible;
//   height: auto;
//   width: 100%;
// }

// .truncate-value a:hover {
//   white-space: normal;
//   overflow: visible;
//   // height: auto;
//   width: 100%;
// }
