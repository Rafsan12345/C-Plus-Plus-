................................................................................................. POLYMARPHISM 
#include <iostream>
using namespace std;
class Animal 
{
  public:
  
   virtual void Sound()
  {
    cout << "Animal gew gew!\n";
  }
  
};



class dog : public Animal 
{
  public:
  
   void Sound() override
  {
    cout << "dog gew gew!\n";
  }
  
};



class cat : public Animal 
{
  public:
  
   void Sound() override
  {
    cout << "cat gew gew!\n";
  }
  
};


int main() 
{
  Animal * a;
  Animal am;
  dog    dd;
  a = &am;
    
  a->Sound();
  
    
    return 0;
}


...........................................................................................POLYMARPHISM 
