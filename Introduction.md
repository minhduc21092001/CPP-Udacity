# Introduction to C++
---
## Course 1: Welcome
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)
![alt text](image-11.png)
![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)
![alt text](image-15.png)
![alt text](image-16.png)
![alt text](image-17.png)
![alt text](image-18.png)
![alt text](image-19.png)
![alt text](image-20.png)
![alt text](image-21.png)
![alt text](image-22.png)
![alt text](image-23.png)
![alt text](image-24.png)
**Standard Library**
![alt text](image-25.png)
![alt text](image-26.png)
**Compilation**
![alt text](image-27.png)
![alt text](image-28.png)
![alt text](image-29.png)
**Build Tools**
![alt text](image-30.png)
![alt text](image-31.png)
![alt text](image-32.png)
![alt text](image-33.png)
**Installation**
![alt text](image-34.png)
![alt text](image-35.png)
![alt text](image-36.png)
![alt text](image-37.png)
![alt text](image-38.png)
![alt text](image-39.png)
![alt text](image-40.png)
![alt text](image-41.png)
**Editors**
![alt text](image-42.png)
![alt text](image-43.png)
![alt text](image-44.png)
**Style**
![alt text](image-45.png)
**Debugging**
![alt text](image-46.png)
**Introduction to Workspaces**
![alt text](image-47.png)
**Notebook Workspaces**
![alt text](image-48.png)
![alt text](image-49.png)
**Terminal Workspaces**
![alt text](image-50.png)
![alt text](image-51.png)
**Desktop Workspaces**
![alt text](image-52.png)
![alt text](image-53.png)
**Submitting Projects**
![alt text](image-54.png)
![alt text](image-56.png)
**Resetting and Refreshing Workspaces**
![alt text](image-57.png)
![alt text](image-58.png)
![alt text](image-59.png)
![alt text](image-60.png)
**What It Takes**
![alt text](image-61.png)
**Getting Help**
![alt text](image-62.png)
**Mentor Help**
![alt text](image-63.png)
![alt text](image-64.png)
![alt text](image-65.png)
**Submitting Classroom Feedback**
![alt text](image-66.png)
![alt text](image-67.png)
![alt text](image-68.png)
![alt text](image-69.png)
![alt text](image-70.png)
**Help Center**
![alt text](image-71.png)
**Udacity Support Community**
![alt text](image-72.png)
**Plagiarism**
![alt text](image-73.png)
![alt text](image-74.png)
![alt text](image-75.png)

## Course 2: C++ Foundations
**The Core Guidelines**
![alt text](image-76.png)
![alt text](image-78.png)
**CODE: Write and Run Your First C++ Program**
![alt text](image-79.png)
![alt text](image-80.png)
![alt text](image-81.png)
**Compiled Languages vs Scripted Languages**
![alt text](image-82.png)
**CODE: Send Output to the Console**
![alt text](image-83.png)
![alt text](image-84.png)
**Bjarne Introduces C++ Types**
![alt text](image-85.png)
**Primitive Variable Types**
![alt text](image-86.png)
**Vectors**
![alt text](image-87.png)
![alt text](image-89.png)
![alt text](image-90.png)
![alt text](image-91.png)
![alt text](image-92.png)
**Comments**
![alt text](image-93.png)
**Using auto**
![alt text](image-94.png)
![alt text](image-95.png)
![alt text](image-96.png)
![alt text](image-97.png)
![alt text](image-98.png)
**CODE: Store a Grid in Your Program**
![alt text](image-99.png)
![alt text](image-100.png)
![alt text](image-101.png)
**Getting Ready for Printing**
![alt text](image-102.png)
**Working with Vectors**
![alt text](image-103.png)
![alt text](image-104.png)
![alt text](image-105.png)
![alt text](image-106.png)
![alt text](image-107.png)
![alt text](image-108.png)
![alt text](image-109.png)
![alt text](image-110.png)
![alt text](image-111.png)
![alt text](image-112.png)
**For Loops**
![alt text](image-113.png)
![alt text](image-114.png)
![alt text](image-115.png)
![alt text](image-116.png)
![alt text](image-117.png)
![alt text](image-118.png)
![alt text](image-119.png)
![alt text](image-120.png)
![alt text](image-121.png)
![alt text](image-122.png)
![alt text](image-123.png)
![alt text](image-124.png)
![alt text](image-125.png)
![alt text](image-126.png)
![alt text](image-127.png)
![alt text](image-128.png)
![alt text](image-129.png)
![alt text](image-130.png)
![alt text](image-131.png)
![alt text](image-132.png)
![alt text](image-133.png)
**CODE: Print the Board**
![alt text](image-134.png)
```C++
#include <iostream>
#include <vector>
using std::cout;
using std::vector;

void PrintBoard(const vector<vector<int>> board) {
  for (int i = 0; i < board.size(); i++) {
    for (int j = 0; j < board[i].size(); j++) {
      cout << board[i][j];
    }
    cout << "\n";
  }
}

int main() {
  vector<vector<int>> board{{0, 1, 0, 0, 0, 0},
                            {0, 1, 0, 0, 0, 0},
                            {0, 1, 0, 0, 0, 0},
                            {0, 1, 0, 0, 0, 0},
                            {0, 0, 0, 0, 1, 0}};
  PrintBoard(board);
}
```
**If Statements and While Loops**
![alt text](image-135.png)
![alt text](image-136.png)
![alt text](image-137.png)
![alt text](image-138.png)
![alt text](image-139.png)
![alt text](image-140.png)
**Reading from a File**
![alt text](image-141.png)
![alt text](image-142.png)
![alt text](image-143.png)
![alt text](image-144.png)
![alt text](image-145.png)
![alt text](image-146.png)
**CODE: Read the Board from a File**
![alt text](image-147.png)
![alt text](image-148.png)
```C++
#include <fstream>
#include <iostream>
#include <string>
#include <vector>
using std::cout;
using std::ifstream;
using std::string;
using std::vector;


void ReadBoardFile(string path) {
  ifstream myfile (path);
  if (myfile) {
    string line;
    while (getline(myfile, line)) {
      cout << line << "\n";
    }
  }
}

// PrintBoard not used in this exercise
void PrintBoard(const vector<vector<int>> board) {
  for (int i = 0; i < board.size(); i++) {
    for (int j = 0; j < board[i].size(); j++) {
      cout << board[i][j];
    }
    cout << "\n";
  }
}

int main() {
  // TODO: Call the ReadBoardFile function here.
  
  // Leave the following line commented out.
  //PrintBoard(board);
}
```
**Processing Strings**
![alt text](image-149.png)
![alt text](image-150.png)
![alt text](image-151.png)
![alt text](image-152.png)
![alt text](image-153.png)
![alt text](image-154.png)
![alt text](image-155.png)
![alt text](image-156.png)
![alt text](image-157.png)
![alt text](image-158.png)