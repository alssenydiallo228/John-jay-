#include <iostream>
#include <vector>
#include <string>
using namespace std;

int main() {
    vector<string> menu;

    menu.push_back("Pizza");
    menu.push_back("Chicken");
    menu.push_back("Burger");
    menu.push_back("Salad");
    menu.push_back("Pasta");

    // Insert a new dish at the 2nd position
    menu.insert(menu.begin() + 1, "Tacos");

    // Remove the 4th dish
    menu.erase(menu.begin() + 3);

    // Print the final menu
    cout << "Final Menu:" << endl;

    for (string dish : menu) {
        cout << dish << endl;
    }

    return 0;
}
