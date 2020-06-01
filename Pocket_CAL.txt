Create calculator using C++ program
#includeiostream
using namespace std;

int main()
{
    char a;
    float num1, num2;

    It allows user to enter operator
    cout  First enter either operator +, -, ,  n;
    cin  a;

    cout  Enter 1st Number ;
    cin  num1;

    cout  Enter 2nd Number ;
    cin  num2;

    switch(a)
    {
        case '+'
            cout  num1+num2;
            break;

        case '-'
            cout  num1-num2;
            break;

        case ''
            cout  num1num2;
            break;

        case ''
            cout  num1num2;
            break;

        default
             If the operator is other than +, -,  or  error message is shown
            cout  Error!!! operator is not correct;
            break;
    }

    return 0;
}
