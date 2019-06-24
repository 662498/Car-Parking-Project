#include<iostream>
#include<windows.h>
#include<stdio.h> 
#include<stdlib.h>
#include<time.h>
void parking ();
using namespace std;
int main ()
{
	system("color 03");
	parking();
	return 0;
}
void parking ()
{
	char a;
	int b,r,q;
	time_t my_time = time(NULL); 
	for(int n=0;n<=19;n++)
    {
    cout<<endl;
    }
    printf("\t\t\t\t\t\t\t\tLoading Please Wait ... ");
    for(r=1;r<=20;r++)
	{
    for(q=0;q<=100000000;q++);
    printf("%c",177);
	}
	system("cls");
	cout<<endl;	
	system("color 09");
	cout<<"\t\t\t\t\t\t\t\t\t LGU PARKING SYSTEM"<<endl;
	x:cout<<"Enter Your Vehicle Type"<<endl;
	cout<<"Press 1 for Car"<<endl;
	cout<<"Press 2 for Bike"<<endl;
	cout<<"Press 3 for Van"<<endl;
	cout<<"Press 4 for Exit"<<endl;
	cin>>a;
	switch(a)
	{
		case'1':
			{
				cout<<"LGU PARKING SYSTEM"<<endl;
				cout<<"Vehicle Type: Car"<<endl;
				y:cout<<"Enter Vehicle Number"<<endl;
				cin>>b;
			    if(b<=10000)
				cout<<"Vehicle Number:"<<" "<<b<<endl;
			    else
			    {
			    cout<<"Invalid Vehicle Number Enter again"<<endl;
			    goto y;
			    }
				cout<<"Time In:";	
				printf("%s", ctime(&my_time));
				cout << '\a'; 
					Beep(523,1150);  // 523 hertz (C5) for 1150 milliseconds
				cout<<endl;	
				goto x;
				break;
			}
		case'2':
			{
		    	cout<<"LGU PARKING SYSTEM"<<endl;
				cout<<"Vehicle Type: Bike"<<endl;
				m:cout<<"Enter Vehicle Number"<<endl;
				cin>>b;
				if(b<=10000)
				{
				cout<<"Vehicle Number:"<<" "<<b<<endl;
			    }
			    else
			    {
			    cout<<"Invalid Vehicle Number Enter Again"<<endl;
			    goto m;
			    }
				cout<<"Time In:";	
				printf("%s", ctime(&my_time));
				cout << '\a';
					Beep(523,1150);  // 523 hertz (C5) for 1150 milliseconds
				cout<<endl;
				goto x;
				break; 	
			}
		case'3':
			{
			    cout<<"LGU PARKING SYSTEM"<<endl;
				cout<<"Vehicle Type: Van"<<endl;
				n:cout<<"Enter Vehicle Number"<<endl;
				cin>>b;
				if(b<=10000)
				{
				cout<<"Vehicle Number:"<<" "<<b<<endl;
			    }
			    else
			    {
			    cout<<"Invalid Vehicle Number Enter again"<<endl;
			    goto n;
			    }
				cout<<"Time In:";	
				printf("%s", ctime(&my_time));
				cout << '\a';
					Beep(523,1150);  // 523 hertz (C5) for 1150 milliseconds
				cout<<endl; 	
				goto x;
				break;	
			}
		case'4':
			{
				cout<<"Thanks for Coming"<<endl;
				cout<<"Time Out:";	
				printf("%s", ctime(&my_time));
				cout << '\a';
					Beep(523,1150);  // 523 hertz (C5) for 1150 milliseconds 	
				break;	
			}
		default:
			{
				cout<<"Invalid Input Enter Again"<<endl;
				cout<<endl;
				goto x;
			}
		}
}
