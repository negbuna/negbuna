```cpp
#include <iostream>
using namespace std;

struct Me {
    string name = "Nathan";
    int age = 16;
    string interests[2] = {"machine learning", "app development"};

    void introduce() {
        cout << name << " | " << age << endl;
        cout << "interests: " << interests[0] << ", " << interests[1] << endl;
    }
};

int main() {
    Me me;
    me.introduce();
    return 0;
}
```
