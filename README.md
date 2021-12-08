# lab05
 Лабораторна робота номер 5, цикли

Горбань |Кирило КІТ-121д
визначити Найбільший спільний дільник

Основна частина:
- описать роботи основної функції: 
- перелік вхідних даних:
   a - перше число
   b - друге число 
   NOD - найбільший спільний дільник
- исследование результатов роботов программирования:
  int main(){
int a,b,NOD;
a = 2048;
b = 798;
while(a != 0){
        if (a >= b){
                a %= b;
                }
        else{ b %= a;
}
}
if(a == 0){
        NOD = b;
}
else{
        NOD = a;
}
return 0;
}

   - при значенні a = 2048; b = 798; NOD = 2
   - для підтвердження коректності роботи програми, зупинен відлагодник на строцы с "return 0" и введемо команду "print NOD". Після вводу команди отримали наступне:
	(lldb) print NOD
	 $1 = 2
Структура проекту лабораторної роботи:

	.
	└── lab03
	    ├── README.txt
	    ├── Makefile
	    └── src
	        └── main.c

Висновки: при виконанні лабораторної роботи буди набуті практичні навички по роботі з циклами на мові С, зокрема: визначити найбільший спільний дільник
