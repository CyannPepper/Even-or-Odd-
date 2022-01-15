# Even-or-Odd-
My solution to a Codecademy practice problem in Javascript that determines if a number is even or odd.


const isEven = (num) => {
  // Gets last digit of inputted number after converting to string and back
  let toText = num.toString();
  let lastChar = toText.slice(-1);
  let lastDigit = +(lastChar);

  // console.log(lastDigit);

// evaluates if true based on if last digit is 0, 2, 4, 6, or 8.
  switch (lastDigit) {
    case (0):
    return true;
    case (2):
    return true;
    case (4):
    return true;
    case (6):
    return true;
    case (8):
    return true;
    default:
    return false;
  }
}; 

console.log(isEven(157));
