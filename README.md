#include <iostream>
using namespace std;

//int main() {
//	int weeknum, monthnum;
	//	cout << "Enter number of day 1-7 : " << endl;
	//	cin >> weeknum;
	//	switch (weeknum)
	//	{
	//	case 1:
	//		cout << "Monday" << endl;
	//		break;
	//	case 2:
	//		cout << "Tuesday" << endl;
	//		break;
	//	case 3:
	//		cout << "Wednesday" << endl; \
	//		break;
	//	case 4:
	//		cout << "Thursday" << endl;
	//		break;
	//	case 5:
	//		cout << "Friday" << endl;
	//		break;
	//	case 6:
	//		cout << "Saturday" << endl;
	//		break;
	//	case 7:
	//		cout << "Sunday" << endl;
	//		break;
	//	default:
	//		break;
	//	}
	//}


	//	cout << "Enter number of the month 1-12 : " << endl;
	//	cin >> monthnum;
	//	switch (monthnum)
	//	{
	//	case 1:
	//		cout << "January" << endl;
	//		break;
	//	case 2:
	//		cout << "February" << endl;
	//		break;
	//	case 3:
	//		cout << "March" << endl; \
	//			break;
	//	case 4:
	//		cout << "April" << endl;
	//		break;
	//	case 5:
	//		cout << "May" << endl;
	//		break;
	//	case 6:
	//		cout << "June" << endl;
	//		break;
	//	case 7:
	//		cout << "July" << endl;
	//		break;
	//	case 8:
	//		cout << "August" << endl;
	//		break;
	//	case 9:
	//		cout << "September" << endl;
	//		break;
	//	case 10:
	//		cout << "October" << endl; \
	//			break;
	//	case 11:
	//		cout << "November" << endl;
	//		break;
	//	case 12:
	//		cout << "December" << endl;
	//		break;
	//	default:
	//		break;
	//	}
	//}

//int main()
//{
//	int a1, a2;
//	cin >> a1 >> a2;
//	if (a1 > a2)
//		cout << "pirmais skaitlis max";
//
//
//	else cout << "otrais skaitlis max";
//	if (a1 < 0)cout << "pirmais skaitlis ir negatīvais";
//	else cout << "pirmais skaitlis ir pozitīvais";
//	if (a2 < 0)cout << "pirmais skaitlis ir negatīvais";
//
//
//	if (a1 < 2) cout << "pirmais skaitlis ir para";
//
//	else cout << "pirmais skaitlis ir nepara";
//}

int main()
{
	int x;
	cout << "Uzrakstīt jūsu procentus";
	cin >> x;
	if (x >= 90)
	{
		cout << "Grade A";
	}
	if (x >= 80 && x < 90) { cout << "Grade B"; }
	if (x >= 70 && x < 80) { cout << "Grade C"; }
	if (x >= 60 && x > 70) { cout << "Grade D"; }
	if (x >= 40 && x > 60) { cout << "Grade E"; }
	if (x < 40) { cout << "Grade F"; }
}
