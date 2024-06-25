#include <iostream>

void drawTriangle(int n) {
    for (int i = 1; i <= n; ++i) {
        for (int j = 1; j <= i; ++j) {
            std::cout << "* ";
        }
        std::cout << std::endl;
    }
}

int main() {
    int height;
    std::cout << "Напишите высоту треугольника: ";
    std::cin >> height;

    drawTriangle(height);

    return 0;
}



