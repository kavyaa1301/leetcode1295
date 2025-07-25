# leetcode1295
Description :
This C++ code defines a class Solution with a method findNumbers that counts how many numbers in a given array have an even number of digits.

How It Works ?
The function checks each number in the input array (nums) and increments the counter (ans) if:

The number is between 10 and 99 (2 digits),
The number is between 1000 and 9999 (4 digits),
The number is exactly 100000 (6 digits).

Example :
int main() {
    Solution sol;
    std::vector<int> nums = {12, 345, 2, 7896, 100000};
    int result = sol.findNumbers(nums);
    std::cout << "Numbers with even digits: " << result << std::endl;
    return 0;
}
Output:
Numbers with even digits: 3
(Explanation: 12 (2 digits), 7896 (4 digits), and 100000 (6 digits) are counted.)

Dependencies:
C++ Standard Library (<iostream>, <vector>)

How to Run:
Save the code in a .cpp file (e.g., even_digits.cpp).

Compile and run


