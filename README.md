#include<iostream>
#include<conio.h>
using namespace std;
main()
class employee {
	private:
		char name[20];
		static int basicpay;
		int allowance;
	public:
		void showdata();
		void getdata();
{
cout<<”name”;
gets (this->name);
cout<<”basicpay opuul”;
cin>>this->basicpay;
cout<<”allowance opuul”;
cin>>this->allowance;
}
};
void employee :: showdata()
{
	cout<<endl;
	cout<<setw(20) <<name;
	cout<<setw(10) <<basicpay;
	cout<<setw(15)<<allowance;
}
main()
{
	employee e;
	e.getdata();
	e.showdata();
	getch();
}
