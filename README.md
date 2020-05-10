# Joshua-s-Repositary

 Package mainpage;
Import java.util.*;
Public class AreaofCirlcleRectangleTriangleSquareTrapezoid {
Public status double AreaofCircle(double radius)
{
 return 3.14*radius*radius;
}
Public static double AreaofRectangle(double length, double breadth)
{
 return length*breadth;
}
Public static double AreaofTriangle(double base, double height)
{ return (base*height)/2;
}
Public static double AreaofSquare(double length)
{
 return length*length;
}
Public static double AreaofTrapezoid(double base, double height )
{ 
 return 0.5*(base+base)*height ;
} 
Public static void main(String[] args)
{
  Scanner sc= new Scanner (System.in);
System.out.print(“Enter the radius of circle”);
double radius = sc.nextDouble() ;

System.out.print(“Enter the length of Rectangle”);
double length = sc.nextDouble();
System.out.print(“Enter the breadth of Rectangle”);
Double breadth = sc.nextDouble();

System.out.print(“Enter the base of Triangle”);
double base = sc.nextDouble();
System.out.print(“Enter the height of Triangle”);
double height = sc.nextDouble();

System.out.print(“Enter the length of Square”);
double length = sc.nextDouble();

System.out.print(“Enter the base of Trapezoid”);
double base = sc.nextDouble();
System.out.print(“Enter  the height of Trapezoid”);
double height = sc.nextDouble();

double areaofcircle = AreaofCircle(radius);
System.out.printIn(“The area of Circle is: ”+areaofcircle);

double areaofrectangle = AreaofRectangle(length, breadth);
System.out.printIn(“The area of Rectangle is: ”+areaofrectangle);

double areaoftriangle = AreaofTriangle(base, height);
System.out.printIn(“The area of Triangle is: ”+areaoftriangle);

double areaofsquare = AreaofSquare(length, length);
System.out.print(“The area of Square is: ”+areaofsquare);

double areaoftrapezoid(base, height );
System.out.print(“The area of Trapezoid is ”+areaoftrapezoid);
  }
}


Import java.util.scanner;
Public class CircumferenceofCircle{
Public static void main(String args[]) {
Int radius;
double circumference;
Scanner sc = new scanner(System.in);
System.out.printIn(“Enter the radius of the circle ::”);
radius = sc.nextInt();
circumference = Math.3.14*2*radius;
System.out.printIn(“Circumference of the circle is ::”+circumference);
  }
}

Import java.util.Scanner;
Class  SurfaceAreaOfCube
{
Public static void main(Stingargs[])
{
Scanner s= new Scanner(System.in);
System.out.printIn(“Enter the side of cube: ”);
double side=s.nextDouble();
double a=SurfaceAreaOfCube.area(side);
System.out.printIn(“SurfaceArea Of Cube is : ”+a);
}
Public static double area(double side)
{
double a=4*side*side;
  return a;
}
} 



Import java.util.Scanner;
Class VolumeOfCylinder
{
Public static void main(String args[])
{
Scanner s= new Scanner(System.in);
System.out.printIn(“Enter the radius: ”);
double r=s.nextDouble();
System.out.printIn(“Enter the height: ”);
double h=s.nextDouble();
double volume=((22*r*r*h)/7);
System.out.printIn(“volume of Cylinder is: ”+volume);
}
}


Import java.util.Scanner;
Class TotalSurfaceAreaOfCylinder
{
 Public static void main(String args[] )
{
Scanner s= new Scanner(System.in);
System.out.printIn(“Enter the length of cuboid:”);
double r=s.nextDouble();
System.out.printIn(“Enter the breadth of cuboid:”);
double h=s.nextDouble();
double tsa=TotalSurfaceAreaOfCylinder.area(r,h);
System.out.printIn(“TotalSurfaceArea Of Cylinder is: ”+tsa);
}
Public static double area(double r, double h)
}
double a= ((2*22*r)/7)*(r+h);
return a;
}
}    
