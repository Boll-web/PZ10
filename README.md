# PZ10
Ex1
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    for (int i = 1; i <= N; i++) {
    cout << i << " ";
}

    

    return 0;
}
```
Ex2
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    for (int i = N; i >= 1; i--) {
        cout << i;
        if (i > 1) {
            cout << " ";
        }
    }
    

    return 0;
}

```
Ex3
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    int sum = 0;
    for (int i = 1; i <= N; i++) {
        sum += i;
    }
    cout << sum << endl;

    return 0;
}

```
Ex4
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    for (int i = 1; i <= N; i++)
        if (i % 2 == 0)
            cout<< i<< " ";
    // Ваш код:


    return 0;
}
```
Ex5
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
     int x = 0; // счётчик чётных чисел
   

    // Перебираем все числа от 1 до N включительно
    for (int i = 1; i <= N; i++) {
        // Проверяем, чётное ли число (остаток от деления на 2 равен 0)
        if (i % 2 == 0) {
            x++; // увеличиваем счётчик на 1, если число чётное
        }
    }

    cout << x << endl;

    return 0;
}

```
Ex6
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int x = 1;
    for(int i = N; i >= 1; i--)
        x = i * x;

    // Ваш код:

    cout << x;
    return 0;
}
```
Ex7
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

   
    for (int i = 1; i <= 10; i++) {
       
        cout << N << " * " << i << " = " << N * i << endl;
    }

    return 0;
}

```
Ex8
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    for (int i = 0; i < N; i++) {
        for (int x = 0; x < N; x++) {
            cout << "*";
        }
        cout << endl;
    }

    return 0;
}

```
