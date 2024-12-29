# Datastructures & Algorithms

## Pointer Reveison

```cpp
//
//  main.cpp
//  Datastructures & Algorithms
//
//  Created by Eng Mahmoud Majed on 28/12/2024.
//

// 1- Pointers -> المؤشر
/*
 int c = 12; this var has address and size and we can control in side By pointer
 &  => called refernce give me memory address for this var and put it before var name
 *& => give me value in this address which make it busy
 *var => pointer => var can store address just inside it and have same type
 we can write in two way
 -datatype* p1;
 -datatype *p1; => Best Practice
 *pointer => return value in this address
 
 ----
 #include <iostream>
 using namespace std;

 int main() {
     int c = 10;
 //    float v =1.2f;
     cout<<sizeof(c)<<"\n";
     cout<<&c<<endl;
     //----
     cout<<*&c<<endl;
     
     return 0;
 }
 ----------- Second
 #include <iostream>
 using namespace std;

 int main() {

     float v =1.2f;
     cout<<sizeof(v)<<"\n";
     cout<<&v<<endl;
     float *z =&v;
     cout<<z<<endl;
     //----
     cout<<*&v<<endl;
     
     return 0;
 }

-----------
 #include <iostream>
 using namespace std;

 int main() {

     float v =1.2f;
     cout<<sizeof(v)<<"\n";
     cout<<&v<<endl;
     float *z =&v;
     cout<<z<<endl;
     cout<<&v<<endl;
     //----
     cout<<*&v<<endl;
     //----
     cout<<*z<<endl;
     
     return 0;
 }
 
-----------
 #include <iostream>
 using namespace std;

 int main() {
     float num =1.5;
     float *ptr =&num;
     float b = *ptr; //we cant store value of ptr
     cout<<b<<"\n";
     
     
     return 0;
 }
 -------
 new keyword -> allocate to size on memory
 
 
 */

#include <iostream>
using namespace std;

int main() {
    float num =1.5;
    float *ptr =&num;
    float b = *ptr; //we cant store value of ptr
    cout<<b<<"\n";
    
    
    return 0;
}


```

## Array  -> Reveison

```cpp
//
//  main.cpp
//  Datastructures & Algorithms
//
//  Created by Eng Mahmoud Majed on 28/12/2024.
//

// 1- Array and Struct

/*
 int arr[];
 
 int x =10;                 | take place (address in memory)
 int arr[5]={1,2,3,4,5}     | address of array the same of the first item &arr = &arr[0]
 array -> take alot of items but fixed
 
 --------
 #include <iostream>
 using namespace std;

 int main() {
     int arr[]={1,2,3,4,5};
     cout<<&arr<<"\n";
     cout<<&arr[0]<<"\n";
     cout<<"------------"<<"\n";
     cout<<&arr[1]<<"\n";
     cout<<"------------"<<"\n";
     cout<<*&arr<<"\n"; //will print random value
     cout<<*&arr[0]<<"\n";
     cout<<"------------"<<"\n";
     return 0;
 }
 
 -------- array Problem and must have size
 #include <iostream>
 using namespace std;

 int main() {
     
     const int size = 100;
     int arr[size];
     int s;
     cout<<"Enter size for array"<<endl;
     cin>>s;
     //------
     for (int i=0;i<s;i++) {
         cout<<"enter number : "<<endl;
         cin>>arr[i];
     }
     for (int j=0;j<s; j++) {
         cout<<" number is : " << arr[j] <<endl;
     }
     
     return 0;
 }
 
 -------- Array with Pointer (important)
 // array is pointer
 
 #include <iostream>
 using namespace std;

 int main() {
     int arr[]={1,2,3,4,5};
     cout<<arr<<endl;        // cout the refrence
     cout<<*&arr<<endl;      //the first will give me to
     cout<<*&arr[4]<<endl;   //will give me the value
     cout<<*arr<<endl;       //give me the value for the first element
     //---- arr+1 //=> next element
     cout<<arr+1<<endl;
     cout<<&arr[1]<<endl;
     cout<<*arr+1<<endl;
     cout<<*(arr+2)<<endl;
     //--------

     cout<<*(&arr+2)<<endl; //now its wrong will give value of address + 2 and give you random value
     return 0;
 }
 
 -------- make array without put size but in runtime
 #include <iostream>
 using namespace std;

 int main() {
     int size;
     cout<<"Enter size"<<endl;
     cin>>size;                  // enter size of array
     int *arr;                   // identifi arr as pointer
     arr=new int [size];         // this will allocate memory space wich user enter it
     for (int i=0; i<size; i++) {
         cout<<"enter number : "<<endl;
         cin>>arr[i];
     }
     for (int j=0; j<size; j++) {
         cout<<arr[j]<<endl;
        
     }
     return 0;
 }

 --------
 
 
 
 --------
 
 */

#include <iostream>
using namespace std;

int main() {
    int size;
    cout<<"Enter size"<<endl;
    cin>>size;                  // enter size of array
    int *arr;                   // identifi arr as pointer
    arr=new int [size];         // this will allocate memory space wich user enter it
    for (int i=0; i<size; i++) {
        cout<<"enter number : "<<endl;
        cin>>arr[i];
    }
    for (int j=0; j<size; j++) {
        cout<<arr[j]<<endl;
       
    }
    return 0;
}


```

## Struct -> Reveison

```cpp


```

##

```cpp


```

##

```cpp


```
