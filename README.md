cout << "enter year\n";
cin >> leapyear;

	
if ((leapyear % 100 == 0) && (leapyear % 400 == 0))
		cout << "leapyear";

else if ((leapyear % 100 > 0) && (leapyear % 4 == 0))

		cout << "leapyear";
else
	cout<<"not leapyear";

return 0;
