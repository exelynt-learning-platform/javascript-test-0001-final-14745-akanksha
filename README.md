# javascript-test-0001-final-14745-akanksha
Final Project Assignment - This repository contains the complete final project code and documentation.


let n = 5;

for (let i = 1; i <= n; i++) {
  let row = "";

 
  for (let j = i; j < n; j++) {
    row += " ";
  }

 
  row += "*";

  
  if (i > 1) {
    for (let k = 1; k <= (2 * i - 3); k++) {
      row += " ";
    }
    row += "*";
  }

  console.log(row);
}


for (let i = n - 1; i >= 1; i--) {
  let row = "";

 
  for (let j = i; j < n; j++) {
    row += " ";
  }


  row += "*";

  
  if (i > 1) {
    for (let k = 1; k <= (2 * i - 3); k++) {
      row += " ";
    }
    row += "*";
  }

  console.log(row);
}
