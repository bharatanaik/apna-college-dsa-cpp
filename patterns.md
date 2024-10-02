# Patterns

## Basic Square pattern

```
1 2 3 4 5
1 2 3 4 5
1 2 3 4 5
1 2 3 4 5
1 2 3 4 5
```
```cpp
for(int i=1; i<=n; i++){
    for(int j=1; j<=n; j++){
        cout << j << " ";
    }
    cout << endl;
}
```
---
```
* * * *
* * * *
* * * *
* * * *
```
```cpp
for(int i=1; i<=n; i++){
    for(int j=1; j<=n; j++){
        cout << "* ";
    }
    cout << endl;
}
```
---
```
A B C D
A B C D
A B C D
A B C D
```
```cpp
for(int i=1; i<=n; i++){
    char c = 'A';
    for(int j=1; j<=n; j++){
        cout << c << " ";
        c++;
    }
    cout << endl;
}
```
---
```
1 2 3
4 5 6
7 8 9
```

```cpp
int k = 1;
for(int i=1; i<=n; i++){
    for(int j=1; j<=n; j++){
        cout << k <<  " ";
        k++;
    }
    cout << endl;1
}
```
---
```
A B C D
E F G H
I J K L
M N O P
```
```cpp
char c = 'A';
for(int i=1; i<=n; i++){
    for(int j=1; j<=n; j++){
        cout << c <<  " ";
        c++;
    }
    cout << endl;
}
```
--- 

## Triangle Pattern

```
*
* *
* * *
* * * *
* * * * *
```
```cpp
for(int i=1; i<=n; i++){
    for(int j=1; j<=i; j++){
        cout <<  "* ";
    }
    cout << endl;
}
```
---

```
1
2 2
3 3 3
4 4 4 4
```

```cpp
for(int i=1; i<=n; i++){
    for(int j=1; j<=i; j++){
        cout <<  i << " ";
    }
    cout << endl;
}
```
---



