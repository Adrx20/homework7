# This is my repository 
### **My name is cat** 
![GitHub](https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_square.jpg)
I'm **java script developer.** *This is Exampleof my code:*
```с++
      int main() {
          vector<int> a;
          vector<int> b;
          int r;
          srand(time(0));
          r = rand() % 10 + 1;
          for (int i = 0; i < 10; i++) {
              a.push_back(r);
              r = rand() % 10 + 1;
          }
          for (int i = 0; i < 10; i++) {
              b.push_back(r);
              r = rand() % 10 + 1;
          }
          cout << "1)" << ' ';
          for (int i = 0; i < 10; i++) {
              cout << a[i] << ' ';
          }
          cout << endl;
      
          cout << "2)" << ' ';
          for (int i = 0; i < 10; i++) {
              cout << b[i] << ' ';
          }
                          
          for (int i = 0; i < 10; i++) {
              a.push_back(b[i]);
          }
      
          cout << endl << "Main)" << ' ';
      
          for (int i = 0; i < a.size(); i++) {
              cout << a[i] << ' ';
          }
      
          for (int i = 0; i < a.size(); i++) {
              for (int j = 0; j < a.size() - 1; j++) {
                  if (a[j] > a[j + 1]) {
                      swap(a[j], a[j + 1]);
                  }
              }
          }
      
          cout << endl << "last int===>" << ' ';
      
          for (int i = 0; i < a.size(); i++) {
              cout << a[i] << ' ';
          }
      }
```
This is Unordered list:
* [My profile in steam](https://steamcommunity.com/profiles/76561199140817467/)
* [My profile in instagram](https://www.instagram.com/aadrrxx/)
* [My profile in github](https://github.com/Adrx20)
