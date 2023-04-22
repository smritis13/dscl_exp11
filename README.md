# dscl_exp11
Guest Lecture
#include <stdio.h>

int linear_search(int arr[], int n, int target) {
    for (int i = 0; i < n; i++) {
        if (arr[i] == target) {
            return i; // Return the index if target found
        }
    }
    return -1; // Return -1 if target not found
}

int main() {
    int arr[] = {3, 8, 4, 1, 9, 5, 7};
    int n = 7; // sizeof(arr) / sizeof(arr[0])
    int target = 5;
    int result = linear_search(arr, n, target);
    if (result == -1) {
        printf("Target value not found in the array.\n");
    } else {
        printf("Target value found at index: %d\n", result);
    }
    return 0;
}
<img width="370" alt="image" src="https://user-images.githubusercontent.com/124857385/233787059-217e595c-95a6-45d7-bff1-bfcb2aec4204.png">
