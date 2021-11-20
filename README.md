# exer25

#include <iostream>
using namespace std;

int main()
{
    float price, sales, Profit, loss;

    cout << "Enter the purchase price: \n";
    cin >> sales;
    cout << "Enter the selling price: \n";
    cin >> price;
    if (price > sales)

    {
        Profit = price - sales;
        cout << "Profit of:\n" << Profit << "dirhams";
    }
    else
    {
        loss = sales - price;
        cout << "loss of\n" << loss << "dirhams";
    }
    return 0;
