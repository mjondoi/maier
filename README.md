# maier#include <conio.h>
#include <stdio.h>
#include <iostream.h>

long gtc(long);
void main()
{
	long n;
	char c;
	do {
		clrscr();
		do { 	cout << "Nhap so nguyen duong n : ";
			cin >> n;
		} while (n < 1);
		cout << n << "!!=" << gtc(n);#include <conio.h>
#include <stdio.h>
#include <iostream.h>

long gtc(long);
void main()
{
		p = bsc(a, b);
		cout << "USCLN(" << a << "," << b << ")=" << d;
		cout << "\nBSCNN(" << a << "," << b << ")=" << p;
		fflush(stdin);
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
	long n;
	char c;
	do {
		clrscr();
		do { 	cout << "Nhap so nguyen duong n : ";
			cin >> n;
		} while (n < 1);
		cout << n << "!!=" << gtc(n);
		fflush(stdin);
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
}

long gtc(long n)
{
	if ((n == 0) || (n == 1)) return 1;
	else return n* gtc(n - 2);
}
		fflush(stdin);
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
}

long gtc(long n)#include <conio.h>
#include <stdio.h>
#include <iostream.h>

long gtc(long);
void main()
{
	long n;
	char c;
	do {
		clrscr();
		do { 	cout << "Nhap so nguyen duong n : ";
			cin >> n;
		} while (n < 1);
		cout << n << "!!=" << gtc(n);
		fflush(stdin);
		p = bsc(a, b);
		cout << "USCLN(" << a << "," << b << ")=" << d;
		cout << "\nBSCNN(" << a << "," << b << ")=" << p;
		fflush(stdin);
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
}

long gtc(long n)
{
	if ((n == 0) || (n == 1)) return 1;
	else return n* gtc(n - 2);
}
{
	if ((n == 0) || (n == 1)) return 1;
	else return n* gtc(n - 2);
}
