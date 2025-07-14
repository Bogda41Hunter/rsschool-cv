# Bobykin Bogdan
## Contact information
* **Discord:** Bogda41
* **Location:** Russia, Nizhny Novgorod

## Brief information about myself
I want to become a cool developer. Programming has interested me since the eighth grade. At this time I started attending school olympiads in information technology and mathematics.
Give me algorithmic tasks and I will solve them all days long.

## Skills
* HTML
* CSS
* SQL 
* C++ (basic knowledge)
* VS Code

## Code Example
Here is one of my implementations of sorting methods:
```
#include <iostream>
using namespace std;

void bubbleSort(int arr[], int n) {
    // Проходим по массиву n-1 раз
    for (int i = 0; i < n - 1; ++i) {
        bool swapped = false; // Флаг проверки обменов
        
        // Последние i элементов уже отсортированы
        for (int j = 0; j < n - i - 1; ++j) {
            if (arr[j] > arr[j + 1]) {
                // Меняем элементы местами
                swap(arr[j], arr[j + 1]);
                swapped = true;
            }
        }
        
        // Если обменов не было - массив отсортирован
        if (!swapped) break;
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22, 11, 90};
    int n = sizeof(arr) / sizeof(arr[0]);
    
    cout << "До сортировки: ";
    for (int i = 0; i < n; ++i) {
        cout << arr[i] << " ";
    }
    
    bubbleSort(arr, n);
    
    cout << "\nПосле сортировки: ";
    for (int i = 0; i < n; ++i) {
        cout << arr[i] << " ";
    }
    
    return 0;
}
```

## Work experience
I worked at UGMS as a leading software engineer. I also have experience in C++ programming, as I studied it at university. I also have basic knowledge of Unreal Engine blueprints, I wrote my thesis using them in my master's degree.

## Education
Bachelor of Applied Informatics in Economics, Nizhny Novgorod State University of Architecture and Civil Engineering

## Language
**English A1.**