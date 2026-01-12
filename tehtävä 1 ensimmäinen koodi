#include <iostream>
#include <cstdlib>
#include <ctime>

int main() {
    std::srand(std::time(nullptr));
    int luku = std::rand() % 20 + 1;
    int arvaus = 0;

    while (arvaus != luku) {
        std::cout << "Arvaa luku (1-20): ";
        std::cin >> arvaus;

        if (arvaus < luku) {
            std::cout << "Liian pieni" << std::endl;
        } else if (arvaus > luku) {
            std::cout << "Liian suuri" << std::endl;
        } else {
            std::cout << "Oikein!" << std::endl;
        }
    }

    return 0;
}
