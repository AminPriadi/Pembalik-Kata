# Pembalik-Kata
    #include<iostream>
    #include<string.h>
    #include<iomanip>
    using namespace std;
    int main ()
    {
        int i,n,p;
        char let[100];
        cout<<"masukan kata atau kalimat= ";
        cin>>let;
        cout<<"terbalik= ";
        n=strlen(let);
        for (i=n-1;i>=0;i--)
            {
                cout<<let[i];
                }
    }
   # Hasil
   ![img](https://raw.githubusercontent.com/AminPriadi/Pembalik-Kata/master/pembalik%20kata.png)
