# Pablo 3b_36

#include <iostream>
using namespace std;
int main()
{
	int DD, MM, AA;
	char symb;

	//Input
	cout << "Introdueix la teva data de naixement en el format (DD MM AA): ";
	cin >> DD >>symb>> MM >>symb>> AA;
	cout << DD << "/" << MM << "/" << AA;
	cout << endl;
	
	//Output
	switch (MM)
	{
	case 1:
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 2: 
		if ((0 == AA % 4) && (0 != AA % 100) || (0 == AA % 400))
		{
			if ((DD <= 29) && (DD > 0))
				cout << "Data correcta";
			else
				cout << "Error: Dia incorrecte";
		}
		else
		{
			if ((DD <= 28) && (DD > 0))
				cout << "Data correcta";
			else
				cout << "Error: Dia incorrecte";
		}
		break;


	case 3: 
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 4: 
		if ((DD <= 30) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 5: 
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 6: 
		if ((DD <= 30) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 7: 
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 8: 
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 9:
		if ((DD <= 30) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 10:
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 11:
		if ((DD <= 30) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	case 12:
		if ((DD <= 31) && (DD > 0))
			cout << "Data correcta";
		else
			cout << "Error: Dia incorrecte";
		break;


	default:  cout << "Error: Mes incorrecte";
		break;
	
	}
cout << endl;
	

	return 0;
}
