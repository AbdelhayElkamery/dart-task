# dart-task
Task 2

//for loop
import 'dart:io';
void main(List<String> arguments)
{
//sumation number 1to100
  int sumI=0;
  for(int i=1;i<=100;i++){
    sumI+=i;
  }
print('the sum of i=$sumI');
for(int x=0;x<=100;x++){print('$x hasssan');
}

}
//Function
  ss
  import 'dart:io';

void main(List<String> arguments) {
  //get value from user
  print('please enter first number');
  num Numb1 =num.parse(stdin.readLineSync()!);
  print('please enter second number');

  num Numb2 =num.parse(stdin.readLineSync()!);

  Samation(Numb1, Numb2);
  Division(Numb1, Numb2);
  subtraction(Numb1,Numb2);
  Multiplication(Numb1, Numb2);

  }
//addition function use 2 number and parameter

num Samation(num number1,num number2)  {
  num result;
  result=number1+number2;
  print("result of sum =$result");
  return result;
}
//subtraction function use 2 number and parameter
num subtraction(num number1,num number2)  {
  num result;
  result=number1-number2;
  print("result of subtraction =$result");
  return result;
}
//Division function use 2 number and parameters
num Division(num number1,num number2)  {
  num result;
  result=number1/number2;
  print("result of Division =$result");
  return result;
}
//Multiplication function use 2 number and parameter
num Multiplication(num number1,num number2)  {
  num result;
  result=number1*number2;
  print("result of Multiplication =$result");
  return result;
}
