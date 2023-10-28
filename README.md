# 1D-Array
A 1D array in C++ is a linear collection of elements of the same data type, accessed by a single index or subscript. It provides a convenient way to store and manage a sequence of values. The syntax for declaring a 1D array is `datatype arrayName[size]`, where `datatype` specifies the type of data the array will hold, `arrayName` is the chosen name for the array, and `size` represents the number of elements it can hold. For example, `int numbers[5]` creates an integer array capable of holding five elements. 1D arrays are commonly used in a wide range of applications, from simple data storage to complex algorithms and calculations.
## Initializing a 1D array in C++
int main() {</br>
    // Initialize a 1D array with 5 elements</br>
    int myArray[5] = {1, 2, 3, 4, 5};</br>

    // Accessing elements of the 1D array</br>
    cout << "Element at index 2: " << myArray[1] << endl; // Outputs: 2</br>

    return 0;</br>
}
