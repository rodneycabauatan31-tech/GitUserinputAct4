# GitUserinputAct4
import 'dart:io';

void main() {
    print("Enter your AGE: ");
    int? Age = int.parse(stdin.readLineSync()!);
    print("Your age is ${Age}");
    if (Age >= 18) {
      print("Adult");
      }else{
        print("Minor");
      }
      print("Your age is ${Age}");

}