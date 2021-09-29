# Compound-conditions
Lecture 7 Compound conditions Exercises
#include<iostream>
using namespace std;
int main()
{
	string capital;
	cout << "What is the Capital of France? " << endl;
	cin >> capital;
	if (capital == "PARIS" || capital == "paris"|| capital=="Paris")
	{
		cout << "Bingo! the answer is correct" << endl;
	}
	else {
		cout << "Oops! You got the wrong answer" << endl;
	}
	return 0;
}
