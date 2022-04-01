# PSDA_01-Linked-List-C-

        #include <iostream>
        #include <vector>

        using namespace std;

        int main() {

        vector <string> fav_fruit;

        fav_fruit.push_back("Apple");
        fav_fruit.push_back("Orange");
        fav_fruit.push_back("Orange");
        fav_fruit.push_back("Banana");
        fav_fruit.push_back("Mango");

        fav_fruit.insert(fav_fruit.begin() + 2, "Banana");

        fav_fruit.erase(fav_fruit.begin() + 1);
        fav_fruit.erase(fav_fruit.begin() + 2);

        for (int i = 0; i < fav_fruit.size(); i++) {
            cout << fav_fruit[i] << endl;
        }

        return 0;
        }
