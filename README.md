# 13-January-Assignment


Q-1:
#include <iostream>
using namespace std;

class Rectangle
{
    public:
    int length,breadth,a;
    
    int area()
    {
        a = length*breadth;
        return 0;
    }
     Rectangle(){
         length=0;
          breadth=0;
     }
      Rectangle(int x,int y){

         length=x;
         breadth=y;
}
    Rectangle(int x){



         length=z;

         breadth=z;
};

int main() {
   
   Rectangle r1;
   Rectangle r2(10);
   Rectangle r3(10,20);
   cout<<r1.area;
   cout<<r2.area;
   cout<<r3.area;
   
    return 0;
}

Q-2

class tri
{    
   string ss;    
   string name ;    
        public:     
  tri(string ss)    
{        
name = ss;    
}    
tri(){        
name = "I love programming languages ";   
 }        };
public class Programming 
{        
public:        
void main(string[] args) 
{        
tri obj = new tri();        
obj.ss = "cpp";        
cout<<"I love " + obj.ss;  
cout<<obj.name;    
}};





