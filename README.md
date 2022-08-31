# Dart-static-properties-function
Dart-static-properties-function


void main(){
STUDENT std=STUDENT("uni of punjab",33,44.44);
  print(STUDENT.collegeName);
  STUDENT std1=STUDENT("uni of gujrat",66,88.88);
  print(STUDENT.collegeName);
   STUDENT std3=STUDENT("uni of lahore",99,88.88);
    
   print(STUDENT.collegeName);
  
  STUDENT.functionCLASS();//CLASSNAME.FUNCTION()
  std.printSTUDENTINFO();
   std1.printSTUDENTINFO();//OBJECT.FUNCTION
  print(std3.studentROLLNO);
  
  STUDENT.collegeName="univeristy of Lahore";
 print(STUDENT.collegeName);


}
class STUDENT
{
  static late String collegeName;//i a
  late String name;
  
   late int studentROLLNO;
   late double studentGPA;
  
  STUDENT(this.name,this.studentROLLNO,this.studentGPA){
  collegeName=name;}
  void printSTUDENTINFO()// I WILL PRINT NON STATIC PROPERTIES 
  {
    
    print(name);
       print(studentROLLNO);
       print(studentGPA);
    
  }
  static functionCLASS()//I WILL  PRINT CLASS STATIC PROPERTIES
  {
    
    print(collegeName);//i will print  class static properties
  }
  
}







