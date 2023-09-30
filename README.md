# muhheryagungnugrahatugaspbo
kode program dengan membandingkan coding dari C++ ke Java 
#include <iostream>
using namespace std;

int main() {
    int nilai[5] = {85, 90, 75, 60, 70};
    int total = 0;

    for(int i = 0; i < 5; i++) {
        total += nilai[i];
    }

    double rata = total / 5.0;
    cout << "Rata-rata nilai: " << rata << endl;

    return 0;
}
JAVA
public class Main {
    public static void main(String[] args) {
        int[] nilai = {85, 90, 75, 60, 70};
        int total = 0;

        for(int i = 0; i < 5; i++) {
            total += nilai[i];
        }

        double rata = (double) total / 5.0;
        System.out.println("Rata-rata nilai: " + rata);
    }
}
