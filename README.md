# & (uses)

### Bitwise AND 

```c++
int main() {
   boleen T = true;
   bolean F = false;
   cout<< (T&F) 
}
```

### use in  condefine statment 
```c++
int main() {
 if (x=0 && y=0)
     cout <<"x=0, y=0"
}
```


### pass by reference

```c++
int main() {
   const int i = 5;
   i = 10;   
   i++;   
}
```

### Address Of operator
```c++
int main() {
   int x=0;
   int *pointeer = &x;
}
```


# const (uses)

### const values
The const keyword specifies that a variable's value is constant and tells the compiler to prevent the programmer from modifying it.

```c++
int main() {
   const int i = 5;
   i = 10;   
   i++;   
}
```
### The const keyword can also be used in pointer declarations
You can use pointers to constant data as function parameters to prevent the function from modifying a parameter passed through a pointer.

```c++
int main() {
   char *mybuf = 0, *yourbuf;
   char *const aptr = mybuf;
   *aptr = 'a';   
   aptr = yourbuf;   
}
```
### pointer to constant int
```c++
int const* id
```
### array of 5x constant int
```c++
int const id[5]
```
### constant pointer to array of 5x int
```c++
int (*const id)[5]
```
