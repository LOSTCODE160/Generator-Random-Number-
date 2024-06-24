# Generator-Random-Number-
( not truly random but close to random )
This is a simple random number generator program written in C++. It generates a random number between 1 and 6 each time it is run.

## How to Use

1. Compile the program using a C++ compiler.
2. Run the compiled program.
3. The program will display a random number between 1 and 6.(Replace 6 with the desired upper limit.)

## Code

```cpp
#include <iostream>
#include <ctime>
using namespace std;

int main() {
    srand(time(NULL));
    int num = (rand() % 6) + 1;
    cout << "Random Number between 1 to 6: " << num << endl;
    return 0;
}
