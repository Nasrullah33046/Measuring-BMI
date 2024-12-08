# Measuring-BMI

#Instructions

Body Mass Index (BMI) is a measure of health on weight. It can be calculated by taking your weight in kilograms and dividing by the square of your height in meters. Write a program that prompts the user to enter a weight in kilograms and height in meters and displays the BMI. 
BMI = weight/(height x height)

Here is a sample run:
Enter weight in kilograms: 60 <enter>
Enter height in meters: 1.7 <enter>
BMI is 20.76



Coding

#include <iostream>
using namespace std;
int main()
{
    double bmi, height, weight;
    
    cout<<"Enter weight in kilograms:";
    cin>>weight;
    
    cout<<"\nEnter height in meters:";
    cin>>height;
    
    bmi = weight / (height * height);
    
    cout<<"\nBMI is "<<bmi;
    return 0;
}
