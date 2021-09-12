#include <iostream> // подключаем библиотеку ввода и вывода
using namespace std; // используем именное пространство std
int main()
{
	setlocale(LC_ALL, "Rus"); // включаем русский язык
	int x, y;
	cout << "Введите число x : "; cin >> x;
	if (x > 0) {
		y = 7*x*x-3*x+6;
		cout << "y = 7*x*x-3*x+6 = " << y << endl;
	}
	else {
		if (x == 0) {
			y = 0;
			cout << "y = " << y << endl;
		}
		else {
			y = abs(x);
			cout << "y = |x| = " << y << endl;
		}
	}
	system("PAUSE"); // чтобы программа не закрывалась
	return 0; // возвращаем функции main() ноль
}
