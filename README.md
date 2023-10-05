#include <stido.h>
#include <conio.h>
void main()
{
	int x;
	printf_s("nhap so nguyen x: ");
	scanf_s("%d", &x);
	int Fx = (1 + x) / (1 - x);
	int Gx = 3 * ( x ^ 5 ) + 2 * (x) + sqrt x + 1  / (5 * ( x ^ 2) - 3;
	printf_s( "ket qua F(x) la %d", Fx);
	printf_s( "ket qua G(x) la %d", Gx);
	_getch();
}
