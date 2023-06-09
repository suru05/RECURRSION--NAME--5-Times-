# RECURRSION--NAME--5-Times-
#include <iostream>
using namespace std;
int i = 0;
void Name(int i, int N)
{
    if (i > N) {
        return;
    }
    cout << "Surabhi Kumari << endl;
        Name(i + 1, N);
    
    
}
int main()
{
    cout << "hello world" << endl;
    Name(1,5);
    return 0;
}
