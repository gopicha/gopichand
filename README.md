{ "name":"John", "age":30, "car":null }
myObj = { "name":"John", "age":30, "car":null };
x = myObj.name;
myObj = { "name":"John", "age":30, "car":null };
x = myObj["name"];
myObj = { "name":"John", "age":30, "car":null };
for (x in myObj) {
  document.getElementById("demo").innerHTML += x;
}
myObj = { "name":"John", "age":30, "car":null };
for (x in myObj) {
  document.getElementById("demo").innerHTML += myObj[x];
}
myObj = {
  "name":"John",
  "age":30,
  "cars": {
    "car1":"Ford",
    "car2":"BMW",
    "car3":"Fiat"
  }
 }
 x = myObj.cars.car2;
// or:
x = myObj.cars["car2"];
myObj.cars.car2 = "Mercedes";
myObj.cars["car2"] = "Mercedes";
delete myObj.cars.car2;
[ "Ford", "BMW", "Fiat" ]
"name":"John",
"age":30,
"cars":[ "Ford", "BMW", "Fiat" ]
}
for (i in myObj.cars) {
  x += myObj.cars[i];
}
for (i = 0; i < myObj.cars.length; i++) {
  x += myObj.cars[i];
}
myObj = {
  "name":"John",
  "age":30,
  "cars": [
    { "name":"Ford", "models":[ "Fiesta", "Focus", "Mustang" ] },
    { "name":"BMW", "models":[ "320", "X3", "X5" ] },
    { "name":"Fiat", "models":[ "500", "Panda" ] }
  ]
 }
 for (i in myObj.cars) {
  x += "<h1>" + myObj.cars[i].name + "</h1>";
  for (j in myObj.cars[i].models) {
    x += myObj.cars[i].models[j];
  }
}
myObj = {
  "name":"John",
  "age":30,
  "cars": [
    { "name":"Ford", "models":[ "Fiesta", "Focus", "Mustang" ] },
    { "name":"BMW", "models":[ "320", "X3", "X5" ] },
    { "name":"Fiat", "models":[ "500", "Panda" ] }
  ]
 }
 for (i in myObj.cars) {
  x += "<h1>" + myObj.cars[i].name + "</h1>";
  for (j in myObj.cars[i].models) {
    x += myObj.cars[i].models[j];
  }
}
