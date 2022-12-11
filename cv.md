
* HTML/Css
* VS Code
* JavaScript (in process)
* Git/GitHub
* Photoshop
* Figma

# Code Example
```
function brightest(arrColors){
  let Vmax = 0;
  let iRes = null;
  let red, green, blue = null;
  let V = null;
  for (let i = arrColors.length-1; i >= 0; i--) {
    red = parseInt("0x" + arrColors[i].slice(1, 3)),
    green = parseInt("0x" + arrColors[i].slice(3, 5)),
    blue = parseInt("0x" + arrColors[i].slice(5, 7));
    V = Math.max(red,green,blue);
//     console.log(red,green,blue, " ====> V=", V);
    if (V >= Vmax){
      Vmax = V;
      iRes = i;
//       console.log("iRes=", iRes);
    }
//     console.log("Vmax=", Vmax);
  }
//   console.log(arrColors + " -> result ->" + arrColors[iRes]);
  return arrColors[iRes];
}
```

# Education and Courses

* **"Academy of Marketing and Social and Information Technologies-IMSIT" (Krasnodar)**
    * Management
* **Skillbox courses**
    * HTML/CSS
    * JavaScript (in process...)
    * Python (in process...)

# Languages

* **Russian** - native speaker
* **English** - B1