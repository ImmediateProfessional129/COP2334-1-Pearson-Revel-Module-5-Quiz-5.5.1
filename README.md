# COP2334-1-Pearson-Revel-Module-5-Quiz-5.5.1
This is a repository link of the COP2334-1 Pearson Module 5 Revel Quiz 5.5.1

// This program is designed to create a basic interface for a library management system.
// The program allows users to add books, remove books, and search for books by title.

// Include header files
#include <iostream>
using namespace std;
int main() {
  // Declare variables
  char option;
  do
    {
      // Display menu
      cout << "Enter a letter choice: A, S, or E" << endl;
      cin >> option;

      if (option == 'A' || option == 'a')
      {
        cout << "Add book" << endl;
      }
      else if (option == 'S' || option == 's')
      {
        cout << "Search for a book" << endl;
      }
    }
    while (option != 'E' && option != 'e');
}
