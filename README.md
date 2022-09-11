# Home_Work_1
#include <iostream>
using namespace std;
int main()
{
	setlocale(LC_ALL, "Russian");
	float a, b, c;
	cout << "Введите три числа: " << endl;
	cin >> a >> b >> c;
	cout << "Сумма: " << a + b + c << endl;
	cout << "Произведение: " << a * b * c << endl;
	cout << "Среднее арифметическое: " << (a + b + c) / 3 << endl;
}
