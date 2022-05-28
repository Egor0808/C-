  #include <iostream>
using namespace std;

void main(void)
{ 
	setlocale(LC_ALL, "Russian");
	float a, b;
	cin >> a >> b;
	if (a != 0 && b != 0)
		{
		float sum = pow(a, 2) + pow(b, 2);
		float differ = pow(a, 2) - pow(b, 2);
		float pro = pow(a, 2) * pow(b, 2);
		float priv = pow(a, 2) / pow(b, 2);
		cout << sum << endl << differ << endl << pro << endl << priv;
		}
	else 
	{
		cout << "без нулей!";
	}
}
