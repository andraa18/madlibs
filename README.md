#include <iostream>
#include <cmath>

using namespace std;

int main ()
{
	string color, PluralNoun, celebrity;
	
	cout << "enter a color: ";
	getline(cin, color);
	cout << "enter a PluralNoun: ";
	getline(cin, PluralNoun);
	cout << "enter a celebrity: ";
	getline(cin, celebrity);
	
	cout << "Roses are " << color << endl;
	cout << PluralNoun << "are blue" << endl;
	cout << "I love " << celebrity << endl;
	
	return 0;
}
