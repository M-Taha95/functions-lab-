﻿# functions-lab-
void main() {
  List myColors = [
    "white",
    "red",
    "blue",
    "green",
    "pink",
    "yellow",
    "black",
    "orrange"
  ];
  for (var i = 0; i < myColors.length; i++) {
    if (i == 2 || i == 6) {
      print(myColors[i].toString().toUpperCase());
    }
    
    if (i =! 2 || i =! 6 ) {
    myColors = myColors.length
    print("sorry this color contains $myColors and it is not start with a or b .");
    }
  }
}
