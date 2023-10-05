# CGPA-calculator
#include <iostream>
using namespace std;
void Percent()
{
  int Total;
  cout<<"Enter value of total:"; cin>>Total;

  int S1,S2,S3,S4,S5;
  cout<<"Enter values:";
  cin>>S1>>S2>>S3>>S4>>S5;
  cout<<"The values of S1,S2,S3,S4,S5 is:" <<S1<< "," <<S2<< "," <<S3<< "," <<S4<< "," <<S5<<endl;
  int sum =S1+S2+S3+S4+S5;
  cout<<"The sum is : "<<sum<<endl;

  float percent;
  percent = (float(sum)/float(Total))*100;
  cout<< "The percentage is: "<<percent<<"%"<<endl;
  
  float cgpa;
  cgpa = percent/9.5;
  cout<<"The CGPA of student is:"<<cgpa;};
int main()
{
  Percent();
  return 0;
}
