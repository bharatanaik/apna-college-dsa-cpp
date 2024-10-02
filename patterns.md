# Patterns


1. Square patterns

    ```cpp
    #include<iostream>

    using namespace std;

    int main(){
        int n;
        cin >> n;
        for(int i=0; i<n; i++){
            for(int j=0; j<n; j++){
                cout << j+1 << " ";
            }
            cout << endl;
        }
        return 0;
    }
    ```
    Output:
    ```
    5
    1 2 3 4 5
    1 2 3 4 5
    1 2 3 4 5
    1 2 3 4 5
    1 2 3 4 5
    ```

