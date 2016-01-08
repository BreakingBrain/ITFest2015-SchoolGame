![pnc100](https://trello-attachments.s3.amazonaws.com/563ded7cd5caefd0065ea486/750x468/db16be8843fdf22c790d61276843a201/pnc100.jpg)

В созвездии Скорпиона был обнаружен бывший храм джедаев. К сожалению, системе не удается идентифицировать систему для гиперпрыжка, высок риск астронавигационной ошибки. Вам придется сделать это вручную. Инструкции навигатора:

{

use(http://www.sky-map.org/)

hyperJump = 0;

getConstellation("Scorpius");

getAsterismStar("Vrischika");

while (hyperJump < 5) {

jumpTo(getNearestStar());

hyperJump++;

}

return getStarName();

}