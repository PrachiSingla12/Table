#include<iostream>
    using namespace std;
    
    int main() {
    
       cout << "enter the size of the matrix : ";
       int m,n;
       cin >> m;
       cin >> n;
    
       int arr[m][n];
       for(int i=0; i<m; i++)
       {
           for(int j=0; j<n; j++){
               cin >> arr[i][j];
           }
           cout << endl;
       }
       for(int i=0; i<m; i++)
       {
           for(int j=0; j<n; j++){
               cout << arr[i][j] << " ";
           }
           cout << endl;
       }
       return 0;
    }
