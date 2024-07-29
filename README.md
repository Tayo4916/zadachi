# zadachi
Я  начинающий программист, учусь пока на простых задачах.
#include <iostream>
int main()
{
  setlocale(0, "");
  int x, y, z, n, m;
  std::cout << "Полученное число: 546.\nНайти исходное число х.\n";
  y = 546 % 10;
  z = 546 / 10;
  n = z % 10;
  m = z / 10;
  std::cout << "Исходное число: " << n << m << y << std::endl;
}
