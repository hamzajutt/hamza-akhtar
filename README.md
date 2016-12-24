# hamza-akhtar#include<iostream>
#include<cmath>
using namespace std;

class BaseClass
{
private:
	float a,b;
public:
	float ans;
	void firstpart(float);
};

　
class DerivedClass1:public BaseClass
{
private:
	float c,d;
public:
	void secondpart(float);
};

　
class DerivedClass2:public DerivedClass1
{
private:
	float e,f;
public:
	void thirdpart(float);
};
