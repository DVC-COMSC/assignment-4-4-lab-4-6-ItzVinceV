[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8796088&assignment_repo_type=AssignmentRepo)
[A4-3] (https://prezi.com/view/Ry5mVQexn9oiURFBH9QM/)

<!--
## ![A6-1](https://nimbus-screenshots.s3.amazonaws.com/s/31c59c7c689afb721fa60bf9522d57bc.png) -->

## Edit a file "main.cpp"

> Complete the program
>
> > Do not change the file name


### Rewrite the following program. Use a switch statement instead of the if/else if statement.
```
#include <iostream>
using namespace std;
int main()
{
  int selection;
  cout << "Which formula do you want to see?\n\n";
  cout << "1. Area of a circle\n";
  cout << "2. Area of a rectangle\n";
  cout << "3. Area of a cylinder\n"
  cout << "4. None of them!\n";
  cin >> selection;
  if (selection == 1)
    cout << "Pi times radius squared\n";
  else if (selection == 2)
    cout << "Length times width\n";
  else if (selection == 3)
    cout << "Pi times radius squared times height\n";
  else if (selection == 4)
    cout << "Well okay then, good bye!\n";
  else
    cout << << "Not good with numbers, eh?\n";
  return 0;
}
```

