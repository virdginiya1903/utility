
## Switch
Конструкция switch может заменить собой несколько условий if. Вот пример обычного условия с if:

``` let answer;

if (num === 1) {
  answer = "One";
} else if (num === 2) {
  answer = "Two";
} else {
  answer = "Nothing";
}
```
А вот как его можно переписать с помощью switch:
```
switch(num) {
  case 1:  // if (num === 1)
    answer = "One";
    break;

  case 2:  // if (num === 2)
    answer = "Two";
    break;

  default:
    answer = "Nothing";
    break;
}
```
break необходим, чтобы выйти из блока switch. 

#### Арифметические шорткаты:
```
b *= a;    // same as b = b * a
b += a;    // same as b = b + a
b -= a;    // same as b = b - a
b %= a;    // same as b = b % a
```
#### Операторы инкрементирования и декрементирования:
```
// Postfix
let a = 3;
let b;
b = a++;    // b = 3, a = 4

// Prefix
let a = 3;
let b;
b = ++a;    // b = 4, a = 4
```
#### Пример цикла:
```
const factorial = (n) => {
  let result  = 1;

  // initialization↓    condition↓     update↓
  for (let counter = 1; counter <= n; counter++) {
    result *= counter;
  }

  return result;
} ```
