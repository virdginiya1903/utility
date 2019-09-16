# utility
## Switch
Конструкция switch может заменить собой несколько условий if. Вот пример обычного условия с if:

let answer;

if (num === 1) {
  answer = "One";
} else if (num === 2) {
  answer = "Two";
} else {
  answer = "Nothing";
}
А вот как его можно переписать с помощью switch:

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
break необходим, чтобы выйти из блока switch.
