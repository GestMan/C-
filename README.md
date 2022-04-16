#include <iostream>
using namespace std;
int main()
{
	int a, b;
	cout << "baraye mohase tavan adad aval ra vared konid :";
	cin >> a;
	cout << " please enter b :";
	cin >> b;

	cout << pow(a, b);

	getch();

}
 int pow (int a, int b)
{
	int pow=1;
	for (int i = 1; i <= b;i++)
	{
		pow *= a;
	}

	return pow;
}
------------------------------------------------------
#include <iostream>
using namespace std;
int main()
{
	int  a, b,c;
	cout << " adad aval ra vared konid ";
	cin >> a;
	cout << " mazrab mored nazar ra vared konid ? ";
	cin >> b;
	
	for (int i = 1; i <= a; i++)
	{
		c = i % b;
		if (c == 0)
		{
			cout << "hope" << 'end l';

		}
		else
		{
			cout << i << 'end l';
		}


	}

 return();

}
----------------------------------------------------------------
#include <iostream>
using namespace std;
int main()
{
	int b = 1, c = 1, z, k, h;
	cout << " adad mored nazar baraye seri fibonachi ra vared konid: ";
	cin >> h;
	cout << x << " " << c << " ";
	z = b + c;
	cout << z << " ";
	for (k = 1; k <= h - 1; k++) {
		b = c;
		c = z;
		z = b + c;
		cout << z << " ";
	}

	return();
}
----------------------------------------------------------------------
#include <iostream>
using namespace std;
int main()
{
	string a;
	int l,o=0;
	cout << "adad vared kond va enter baznid :";
	cin >> a;
	t = a.length();
	
	for (int u = 0;u < l;i++)
	{
		o = o+(a[u]-48);
	}
	cout << o;

	return();
}
