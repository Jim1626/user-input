import 'dart:io';

void main() {
  print('Enter 1st number:');
  double? number1 = double.parse(stdin.readLineSync()!);

  print('Enter 2nd number:');
  double? number2 = double.parse(stdin.readLineSync()!);

  print('Sum: ${number1 + number2}');
  print('Subtraction: ${number1 - number2}');
  print('Multiplication: ${number1 * number2}');
  print('Division: ${number1 / number2}');
}
