# INSERTION SORT PROJECT
[22,27,16,2,18,6] -> Insertion Sort

## 1.Write the stages of the above given sequence according to the sort type.

### First Pass
[22,27,16,2,18,6] No swap needed since the first two elements[22,27] are in ascending order.

### Second Pass
Compare next two elements[27,16]. Since 16 is smaller than 27, swap them.
* [22,27,16,2,18,6]--->[22,16,27,2,18,6] 

Then, compare element [16] with previous element [22]. Since 16 is smaller than 22, swap them again.
* [22,16,27,2,18,6]--->[16,22,27,2,18,6]

### Third Pass
Compare next two elements[27,2]. Since 2 is smaller than 27, swap them.
* [16,22,27,2,18,6] ---> [16,22,2,27,18,6]

Then, compare element 2 with previous element 22. Since 2 is smaller than 22, swap them again.
* [16,22,2,27,18,6] ---> [16,2,22,27,18,6]

Then compare element 2 with previous element 16. Since 2 is smaller than 16, swap them one last time :).
 * [2,16,22,27,18,6]

 ### Fourth Pass
 Compare next two elements [27,18]. Since 18 is smaller than 27, swap them.
 * [2,16,22,27,18,6] ---> [2,16,22,18,27,6]

 Then compare element 18 with previous element 22. Since 18 is smaller than 22, swap them again.
 * [2,16,22,18,27,6] ---> [2,16,18,22,27,6]

 ### Fifth Pass
 Compare next two elements [27,6]. Since 6 is smaller than 27, swap them. Then swap element 6 with all previous elements which smaller than 6.
 * [2,16,18,22,27,6] ---> [2,16,18,22,6,27] ---> [2,16,18,6,22,27] ---> [2,16,6,18,22,27] ---> [2,6,16,18,22,27]

 ---

## 2.Write the Big-O notation.
* O(n^2)

---

## 3.Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the series.What case does the number 18 fit into after the array is sorted?
* [2,6,16,18,22,27] It is an example of an avarage case.

---


## 4.[7,3,5,8,2,9,4,15,6] Write the first 4 steps of the array according to the Insertion Sort.

### First Pass
* [7,3,5,8,2,9,4,15,6] ---> [3,7,5,8,2,9,4,15,6] ---> [3,5,7,8,2,9,4,15,6]

### Second Pass
* [3,5,7,8,2,9,4,15,6] Since elements [7,8] are in ascending order, no swap needed.

### Third Pass
* [3,5,7,8,2,9,4,15,6] ---> [3,5,7,2,8,9,4,15,6] ---> [3,5,2,7,8,9,4,15,6] ---> [3,2,5,7,8,9,4,15,6] ---> [2,3,5,7,8,9,4,15,6]

### Fourth Pass
* [2,3,5,7,8,9,4,15,6] Since elements [8,9] are in descending order, no swap needed.
---

* Patika.dev link: https://app.patika.dev/yigitmustu