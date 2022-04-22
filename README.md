# destructor-
using System;  
namespace CsharpDestructor 
{
  
  class Person 
{

    public Person()
 {
      Console.WriteLine("Constructor called.");
    }
 
    ~Person() {
      Console.WriteLine("Destructor called.");
    }

    public static void Main(string [] args) 
{

     
      Person p1 = new Person();
    }
  } 
}
