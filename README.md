#include <iostream>
using namespace std;
class A
{
    int a;

public:
    A()
    {
        a = 28;
    }
    
};
void print(A a)
{
    cout << "A = " << a.a;
}

main()
{
    A a;
    print(a);
}
