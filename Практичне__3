#include "pch.h"
#include <iostream>
#include<string>
#include<vector>
using namespace std;
class Football_Club
{
public:
	virtual void Country()
	{
		cout << "Country" << endl;
	}
};
class Barca:public Football_Club
{
private:
	Football_Club *b;
	int LC;
public:
     Barca(Football_Club *_b,int l)
	{
		 b = _b;
		 LC = l;
	}
	 void Country()
	 {
		 b->Country();
		 cout << "Spain"<<" " << "Leage Champion"<<" "<< LC << endl;
	 }

};
class Chelse :public Football_Club
{
private:
	Football_Club *b;
	int LC;
public:
	Chelse(Football_Club *_b, int l)
	{
		b = _b;
		LC = l;
	}
	void Country()
	{
		b->Country();
		cout << "England"<<" " << "Leage Champion"<<" " << LC << endl;
	}

};
class PSG :public Football_Club
{
private:
	Football_Club *b;
	int LC;
public:
	PSG(Football_Club *_b, int l)
	{
		b = _b;
		LC = l;
	}
	void Country()
	{
		b->Country();
		cout << "France" << " " << "Leage Champion" << " " << LC << endl;
	}

};
class Dynamo_Kyiv :public Football_Club
{
private:
	Football_Club *b;
	int LC;
public:
	Dynamo_Kyiv(Football_Club *_b, int l)
	{
		b = _b;
		LC = l;
	}
	void Country()
	{
		b->Country();
		cout << "Ukraine" << " " << "Leage Champion" << " " << LC << endl;
	}

};
int main()
{

	Football_Club* f = new Football_Club();
	Barca* b = new Barca(f,6);
	Chelse* c = new Chelse(b,1);
	PSG *p = new PSG(c, 0);	
	Dynamo_Kyiv*d = new Dynamo_Kyiv(p, 0);
	d->Country();
	
	
	
	


	system("pause");
}

