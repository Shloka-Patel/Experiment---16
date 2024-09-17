# Experiment---16 

#### Aim 
To study and implement Exception Handling in C++. 

#### Software 
Visual Studio Code 

#### Theory 
<ul>
    <li>In C++ exceptions are runtime anomalies or abnormal conditions that a program encounters durig its execution. </li>
    <li>The process of handling these exceptions is known as exception handling. </li> 
    <li>Using the exception handling mechanism, the control from one part of the program where the exception occurred can be transferred to another part of the 
   code.</li>
</ul>

#### Code 

(A) <br> 
```
// NAME - SHLOKA PATEL 
//PRN - 23070123120 
// EXPERIMET - 16(A) 

// EXCEPTION HANDLING 

#include<iostream>
using namespace std;

int main()
{
    float n1, n2, n3, n4, ans;
    cout<<"Enter values of numbers 1 and 2: ";
    cin>>n1>>n2;
    try{
        if(n2==0) {
            throw n2;
        }
        else {
            ans=n1/n2;
            cout<<"Answer = "<<ans<<endl;
        }
    }
    catch(float num) {
        cout<<"\n ERROR: Division by "<<num<<endl;
    }
}
```

(B) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 16(B) 

// EXCEPTION HANDLING 

#include<iostream>
using namespace std;

int main()
{
    int age;
    cout<<"Enter age: ";
    cin>>age;
    try{
        if(age<18) {
            throw age;
        }
        else {
            cout<<"Age: "<<age<<"\n APPROVED"<<endl;
        }
    }
    catch(int a) {
        cout<<"\n ERROR: Underage! ("<<age<<")"<<endl;
    }
}
```

#### Output 

(A) <br> 
![](https://github.com/Shloka-Patel/Experiment---16/blob/main/Output_16A.png) 

(B) <br> 
![](https://github.com/Shloka-Patel/Experiment---16/blob/main/Output_16B.png) 

#### Conclusion 

