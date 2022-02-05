const toUrl = (string) => {
if(string.length == 0) {
  return string;
}
const char = string.charAt(string.length-1);
if (char === " "){
  char = "%20"
}
return toUrl(string + (char - 1));
}

 Problem 1;
const toUrl = (string) => {
  const stringArray = string.split('');
  const result = stringArray.map(function(e){
    if(e===" "){
     return e = "%20";
    } else {
     return e;
    }
})
  return result.join("");
}

Problem 2;
const noDupes = (array) => {
const newArray = [...new Set(array)];
return newArray;
}

Problem 4;
const uniqueCharacters = (string) => {
  const x = 0;
  if(string.substring(x)===string.substring(x+1)
    return false;
  }
    return uniqueCharacters(string) + (x + 1)
  }


  
  
  const x = 0; 
  if (string.substring(string(x)) !== string.substring(x+1)){
      return true;
    }
     return compressStrings(string) + (x + 1);
     }


 
 






