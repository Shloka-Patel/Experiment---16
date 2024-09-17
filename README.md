# Experiment---16 

#### Aim 
To study and implement Exception Handling in C++. 

#### Software 
Visual Studio Code 

#### Theory 

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
```

#### Output 

(A) <br> 
![]() 

(B) <br> 
![]() 

#### Conclusion 

