# Mục lục

1. [Những kiến thức cần học để giải LeetCode bằng JavaScript](#nhung-kien-thuc-can-hoc-de-giai-leetcode-bang-javascript)
2. [JavaScript cơ bản](#javascript-co-ban)
    - [Khai báo biến và kiểu dữ liệu](#khai-bao-bien-va-kieu-du-lieu)
    - [Câu lệnh điều kiện](#cau-lenh-dieu-kien)
    - [Vòng lặp](#vong-lap)
    - [Hàm](#ham)
    - [Thao tác với mảng](#thao-tac-voi-mang)
    - [Bài tập nhỏ](#bai-tap-nho)
3. [Câu lệnh điều kiện nâng cao](#cau-lenh-dieu-kien-nang-cao)
    - [if-else](#if-else)
    - [if-else if-else](#if-else-if-else)
    - [switch-case](#switch-case)
    - [Bài tập luyện tập](#bai-tap-luyen-tap-dieu-kien)
4. [Các loại vòng lặp trong JavaScript](#cac-loai-vong-lap-trong-javascript)
    - [for](#for)
    - [while](#while)
    - [do...while](#do-while)
    - [for...in và for...of](#for-in-va-for-of)
    - [Bài tập luyện tập](#bai-tap-luyen-tap-vong-lap)
5. [Thao tác với mảng](#thao-tac-voi-mang)
    - [Khai báo và truy cập mảng](#khai-bao-va-truy-cap-mang)
    - [Thêm, xóa phần tử](#them-xoa-phan-tu)
    - [Duyệt mảng](#duyet-mang)
    - [Một số phương thức mảng hay dùng](#mot-so-phuong-thuc-mang-hay-dung)
    - [Bài tập luyện tập](#bai-tap-luyen-tap-mang)
6. [Object (Đối tượng) trong JavaScript](#object-doi-tuong-trong-javascript)
    - [Khai báo và truy cập Object](#object-khai-bao-va-truy-cap)
    - [Thêm, sửa, xóa thuộc tính](#object-them-sua-xoa)
    - [Duyệt qua các thuộc tính của Object](#object-duyet-thuoc-tinh)
    - [Một số thao tác thường gặp](#object-thao-tac-thuong-gap)
    - [Bài tập luyện tập](#object-bai-tap)
7. [String (Chuỗi) trong JavaScript](#string-chuoi-trong-javascript)
    - [Khai báo và truy cập ký tự](#string-khai-bao-va-truy-cap)
    - [Một số phương thức chuỗi hay dùng](#string-phuong-thuc-hay-dung)
    - [Bài tập luyện tập](#string-bai-tap)
8. [Cấu trúc dữ liệu nâng cao](#cau-truc-du-lieu-nang-cao)
    - [Set](#set)
    - [Map](#map)
    - [Stack](#stack)
    - [Queue](#queue)
    - [Bài tập luyện tập](#bai-tap-luyen-tap-cau-truc-nang-cao)
9. [Linked List (Danh sách liên kết)](#linked-list-danh-sach-lien-ket)
    - [Khái niệm và cài đặt](#linked-list-khai-niem-va-cai-dat)
    - [Duyệt, thêm, xóa node](#linked-list-duyet-them-xoa)
    - [Bài tập luyện tập](#linked-list-bai-tap)
10. [Tree (Cây nhị phân)](#tree-cay-nhi-phan)
    - [Khái niệm và cài đặt](#tree-khai-niem-va-cai-dat)
    - [Duyệt cây](#tree-duyet-cay)
    - [Bài tập luyện tập](#tree-bai-tap)
11. [Graph (Đồ thị)](#graph-do-thi)
    - [Khái niệm và biểu diễn](#graph-khai-niem-va-bieu-dien)
    - [Thuật toán duyệt đồ thị (BFS, DFS)](#graph-thuat-toan-duyet)
    - [Bài tập luyện tập](#graph-bai-tap)
12. [Thuật toán tìm kiếm và sắp xếp cơ bản](#thuat-toan-tim-kiem-va-sap-xep-co-ban)
    - [Tìm kiếm tuyến tính, nhị phân](#tim-kiem-tuyen-tinh-nhi-phan)
    - [Các thuật toán sắp xếp](#cac-thuat-toan-sap-xep)
    - [Bài tập luyện tập](#tim-kiem-sap-xep-bai-tap)
13. [Thuật toán nâng cao: DP, Backtracking, Greedy](#thuat-toan-nang-cao-dp-backtracking-greedy)
    - [Dynamic Programming](#dynamic-programming)
    - [Backtracking](#backtracking)
    - [Greedy Algorithm](#greedy-algorithm)
    - [Bài tập luyện tập](#dp-backtracking-greedy-bai-tap)
14. [Kỹ thuật Two Pointers và Sliding Window](#ky-thuat-two-pointers-va-sliding-window)
    - [Two Pointers](#two-pointers)
    - [Sliding Window](#sliding-window)
    - [Bài tập luyện tập](#two-pointers-sliding-window-bai-tap)
15. [Bit Manipulation (Xử lý bit)](#bit-manipulation-xu-ly-bit)
    - [Các phép toán bit cơ bản](#cac-phep-toan-bit-co-ban)
    - [Ứng dụng phổ biến](#ung-dung-bit-pho-bien)
    - [Bài tập luyện tập](#bit-manipulation-bai-tap)
16. [Đệ quy nâng cao](#de-quy-nang-cao)
    - [Đệ quy trên cấu trúc dữ liệu](#de-quy-tren-cau-truc-du-lieu)
    - [Đệ quy với memoization](#de-quy-voi-memoization)
    - [Bài tập luyện tập](#de-quy-bai-tap)
17. [Đánh giá độ phức tạp thuật toán và Big O](#danh-gia-do-phuc-tap-thuat-toan-va-big-o)
    - [Big O Notation](#big-o-notation)
    - [Time & Space Complexity](#time-space-complexity)
    - [Bảng so sánh](#bang-so-sanh-big-o)
18. [Trie, Heap, Priority Queue và Chủ đề nâng cao](#trie-heap-priority-queue-va-chu-de-nang-cao)
    - [Trie](#trie)
    - [Heap & Priority Queue](#heap-priority-queue)
    - [Chủ đề LeetCode nâng cao](#chu-de-leetcode-nang-cao)
    - [Bài tập luyện tập](#trie-heap-bai-tap)
19. [Dynamic Programming nâng cao: Bitmask DP](#dynamic-programming-nang-cao-bitmask-dp)
    - [Bitmask DP là gì?](#bitmask-dp-la-gi)
    - [Ứng dụng Bitmask DP](#ung-dung-bitmask-dp)
    - [Bài tập luyện tập](#bitmask-dp-bai-tap)
20. [Advanced Graph Algorithms](#advanced-graph-algorithms)
    - [Dijkstra, Union-Find, Tarjan](#dijkstra-union-find-tarjan)
    - [Segment Tree & Fenwick Tree](#segment-tree-fenwick-tree)
    - [Bài tập luyện tập](#advanced-graph-bai-tap)
21. [Lộ trình luyện LeetCode nâng cao & Kinh nghiệm thực chiến](#lo-trinh-luyen-leetcode-nang-cao-kinh-nghiem-thuc-chien)

--- 

## Những kiến thức cần học để giải LeetCode bằng JavaScript

Để giải quyết hiệu quả các bài tập trên LeetCode bằng JavaScript, bạn cần trang bị các nhóm kiến thức sau:

### 1. Nền tảng JavaScript cơ bản
- Hiểu rõ cú pháp, kiểu dữ liệu, biến, hàm, vòng lặp, điều kiện, thao tác với mảng và object.
- Nắm vững các phương thức xử lý mảng, chuỗi, object giúp code ngắn gọn, tối ưu.

### 2. Cấu trúc dữ liệu cơ bản & nâng cao
- **Array, String, Object**: Sử dụng thành thạo để lưu trữ và xử lý dữ liệu.
- **Stack, Queue, Set, Map**: Hiểu cách cài đặt, thao tác và ứng dụng thực tế.
- **Linked List, Tree, Graph, Heap, Trie**: Nắm được khái niệm, cách cài đặt, các thao tác cơ bản và ứng dụng trong bài toán thực tế.

### 3. Thuật toán cơ bản & nâng cao
- **Tìm kiếm**: Tuyến tính, nhị phân.
- **Sắp xếp**: Bubble, Selection, Insertion, Merge, Quick Sort.
- **Đệ quy, Backtracking, Dynamic Programming, Greedy**: Hiểu bản chất, khi nào áp dụng, cách tối ưu.
- **Kỹ thuật Two Pointers, Sliding Window, Bit Manipulation**: Rất hay gặp trong các bài LeetCode tối ưu.

### 4. Đánh giá độ phức tạp thuật toán
- Hiểu và ước lượng Big O cho thời gian và bộ nhớ.
- Biết cách phân tích, tối ưu giải pháp khi gặp input lớn.

### 5. Kỹ năng giải quyết vấn đề
- Đọc kỹ đề, phân tích ví dụ, xác định input/output rõ ràng.
- Tư duy chia nhỏ bài toán, thử nhiều hướng giải, tối ưu dần.
- Biết debug, kiểm tra kết quả với nhiều test case.

### **Tóm tắt bảng kiến thức cần học**

| Nhóm kiến thức         | Nội dung chính                                                                 |
|-----------------------|-------------------------------------------------------------------------------|
| JavaScript cơ bản     | Biến, kiểu dữ liệu, hàm, vòng lặp, điều kiện, mảng, object, string            |
| Cấu trúc dữ liệu      | Array, Object, Set, Map, Stack, Queue, Linked List, Tree, Graph, Heap, Trie   |
| Thuật toán            | Tìm kiếm, sắp xếp, đệ quy, DP, Backtracking, Greedy, Bit Manipulation         |
| Kỹ thuật nâng cao     | Two Pointers, Sliding Window, State Compression, Union-Find, Segment Tree     |
| Đánh giá độ phức tạp  | Big O, Time/Space Complexity, tối ưu giải pháp                                |

### **Lời khuyên học tập**
- Học từng chủ đề nhỏ, luyện tập nhiều bài dễ trước khi chuyển sang bài nâng cao.
- Tổng hợp lại các mẫu code, mẹo giải nhanh, lỗi thường gặp.
- Thường xuyên review lại các bài đã làm, tối ưu code và phân tích độ phức tạp.
- Tham gia cộng đồng, hỏi đáp, học hỏi kinh nghiệm từ người khác.
- Kiên trì luyện tập đều đặn, đặt mục tiêu giải 1-2 bài/ngày.

**Hãy bắt đầu từ những kiến thức cơ bản nhất, luyện tập đều đặn và từng bước chinh phục các thử thách LeetCode!**

--- 

## JavaScript cơ bản

### Khai báo biến và kiểu dữ liệu

JavaScript hỗ trợ ba cách khai báo biến:
- `let`: Khai báo biến có thể thay đổi giá trị trong block scope.
- `const`: Khai báo biến không thể gán lại giá trị (immutable reference).
- `var`: Cách cũ, phạm vi function scope, ít dùng trong code hiện đại.

**Ví dụ:**
```js
let age = 25;         // số
const name = "Nam";   // chuỗi
var isStudent = true; // boolean
```

**Các kiểu dữ liệu cơ bản:**
- Number (số): `let a = 10;`
- String (chuỗi): `let b = "Hello";`
- Boolean (đúng/sai): `let c = false;`
- Array (mảng): `let arr = [1, 2, 3];`
- Object (đối tượng): `let obj = {name: "Nam", age: 25};`

---

### Câu lệnh điều kiện

Dùng để kiểm tra điều kiện và thực hiện các hành động khác nhau tùy vào kết quả đúng/sai.

**Cú pháp if-else:**
```js
if (điều_kiện) {
  // Code thực hiện nếu điều_kiện đúng
} else {
  // Code thực hiện nếu điều_kiện sai
}
```

**Ví dụ:**
```js
let score = 85;
if (score >= 90) {
  console.log("Xuất sắc");
} else if (score >= 70) {
  console.log("Khá");
} else {
  console.log("Cần cố gắng");
}
```

---

### Vòng lặp

#### For
Dùng khi biết trước số lần lặp.
```js
for (let i = 0; i < 5; i++) {
  console.log(i); // in ra 0,1,2,3,4
}
```

#### While
Dùng khi không biết trước số lần lặp, chỉ biết điều kiện dừng.
```js
let i = 0;
while (i < 3) {
  console.log(i);
  i++;
}
```

#### For...of
Lặp qua các giá trị của mảng, chuỗi.
```js
let arr = [10, 20, 30];
for (let value of arr) {
  console.log(value); // 10, 20, 30
}
```

#### For...in
Lặp qua các key của object.
```js
let obj = {a: 1, b: 2, c: 3};
for (let key in obj) {
  console.log(key, obj[key]); // a 1, b 2, c 3
}
```

---

### Hàm

Hàm giúp đóng gói logic, tái sử dụng nhiều lần.

**Khai báo hàm truyền thống:**
```js
function sum(a, b) {
  return a + b;
}
console.log(sum(3, 4)); // 7
```

**Arrow function:**
```js
const multiply = (a, b) => a * b;
console.log(multiply(2, 5)); // 10
```

---

### Thao tác với mảng

### Khai báo và truy cập mảng

Mảng (Array) là một trong những cấu trúc dữ liệu quan trọng nhất trong JavaScript.

**Khai báo:**
```js
let arr = [1, 2, 3, 4];
```

**Truy cập phần tử:**
```js
console.log(arr[0]); // 1
console.log(arr[2]); // 3
```
- Chỉ số (index) bắt đầu từ 0.

---

### Thêm, xóa phần tử trong mảng

- **Thêm vào cuối:** `arr.push(value)`
- **Xóa cuối:** `arr.pop()`
- **Thêm vào đầu:** `arr.unshift(value)`
- **Xóa đầu:** `arr.shift()`

**Ví dụ:**
```js
let arr = [1, 2, 3];
arr.push(4);      // [1, 2, 3, 4]
arr.pop();        // [1, 2, 3]
arr.unshift(0);   // [0, 1, 2, 3]
arr.shift();      // [1, 2, 3]
```

---

### Duyệt mảng

- **for**
- **for...of**
- **forEach**

**Ví dụ:**
```js
let arr = [10, 20, 30];
arr.forEach(function(value) {
  console.log(value);
});
```

---

### Một số phương thức mảng hay dùng

| Phương thức      | Ý nghĩa                                      | Ví dụ sử dụng                |
|------------------|----------------------------------------------|------------------------------|
| `map`           | Tạo mảng mới bằng cách biến đổi từng phần tử  | `arr.map(x => x * 2)`        |
| `filter`        | Lọc ra các phần tử thỏa mãn điều kiện         | `arr.filter(x => x > 10)`    |
| `reduce`        | Tính toán tích lũy trên mảng                  | `arr.reduce((a, b) => a + b)`|
| `find`          | Tìm phần tử đầu tiên thỏa mãn điều kiện       | `arr.find(x => x % 2 === 0)` |
| `includes`      | Kiểm tra mảng có chứa giá trị nào đó không    | `arr.includes(3)`            |
| `indexOf`       | Tìm vị trí xuất hiện đầu tiên của giá trị     | `arr.indexOf(20)`            |
| `sort`          | Sắp xếp mảng                                  | `arr.sort((a, b) => a - b)`  |
| `reverse`       | Đảo ngược mảng                                | `arr.reverse()`              |

**Ví dụ:**
```js
let arr = [1, 2, 3, 4, 5];
let doubled = arr.map(x => x * 2); // [2, 4, 6, 8, 10]
let even = arr.filter(x => x % 2 === 0); // [2, 4]
let sum = arr.reduce((a, b) => a + b, 0); // 15
let hasThree = arr.includes(3); // true
let idx = arr.indexOf(4); // 3
let sorted = arr.sort((a, b) => b - a); // [5, 4, 3, 2, 1]
let reversed = arr.reverse(); // [1, 2, 3, 4, 5] (nếu gọi sau sort)
```

---

### Bài tập luyện tập mảng

1. Tạo một mảng số nguyên bất kỳ, dùng `map` để tạo mảng mới với mỗi phần tử gấp đôi giá trị ban đầu.
2. Tạo một mảng số nguyên, dùng `filter` để lấy ra các số chẵn.
3. Tính tổng các phần tử của mảng bằng `reduce`.
4. Kiểm tra xem mảng có chứa số 5 hay không bằng `includes`.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị mảng để kiểm tra kết quả.

--- 

## Câu lệnh điều kiện nâng cao

### if-else

Câu lệnh if-else dùng để kiểm tra điều kiện và thực hiện các nhánh khác nhau tùy vào kết quả đúng/sai.

**Cú pháp:**
```js
if (điều_kiện) {
  // Code thực hiện nếu điều_kiện đúng
} else {
  // Code thực hiện nếu điều_kiện sai
}
```

**Ví dụ:**
```js
let age = 18;
if (age >= 18) {
  console.log("Bạn đã đủ tuổi để xem phim này.");
} else {
  console.log("Bạn chưa đủ tuổi để xem phim này.");
}
```

---

### if-else if-else

Dùng khi có nhiều điều kiện cần kiểm tra liên tiếp.

**Cú pháp:**
```js
if (điều_kiện_1) {
  // code nếu điều_kiện_1 đúng
} else if (điều_kiện_2) {
  // code nếu điều_kiện_2 đúng
} else {
  // code nếu không điều kiện nào đúng
}
```

**Ví dụ:**
```js
let score = 75;
if (score >= 90) {
  console.log("Xuất sắc");
} else if (score >= 70) {
  console.log("Khá");
} else {
  console.log("Cần cố gắng");
}
```

---

### switch-case

Dùng khi cần kiểm tra giá trị của một biến với nhiều trường hợp cụ thể.

**Cú pháp:**
```js
switch (biến) {
  case giá_trị_1:
    // code nếu biến === giá_trị_1
    break;
  case giá_trị_2:
    // code nếu biến === giá_trị_2
    break;
  default:
    // code nếu không khớp case nào
    break;
}
```

**Ví dụ:**
```js
let day = "Monday";
switch (day) {
  case "Monday":
    console.log("Today is Monday");
    break;
  case "Tuesday":
    console.log("Today is Tuesday");
    break;
  default:
    console.log("Unknown day");
    break;
}
```

**Lưu ý:**
- `break` giúp chương trình thoát khỏi switch sau khi thực hiện xong một case.
- Nếu không có `break`, chương trình sẽ chạy tiếp các case phía dưới (hiện tượng "rơi qua case").

---

### Bài tập luyện tập điều kiện

1. Viết chương trình kiểm tra một số nguyên `n`. Nếu `n` là số dương, in ra "Số dương", nếu là số âm, in ra "Số âm", nếu là 0, in ra "Số không".
2. Viết chương trình nhập vào biến `fruit` (giả sử là "apple", "banana", "orange"). Dùng switch-case in ra tên tiếng Việt của loại quả đó. Nếu không thuộc các loại trên, in "Không xác định".

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị biến để kiểm tra các nhánh điều kiện.

--- 

## Các loại vòng lặp trong JavaScript

### Vòng lặp for

Dùng khi biết trước số lần lặp.

**Cú pháp:**
```js
for (let i = 0; i < 5; i++) {
  // code sẽ thực hiện 5 lần, với i lần lượt là 0,1,2,3,4
  console.log(i);
}
```

**Ví dụ:** In ra các số từ 1 đến 5
```js
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

---

### Vòng lặp while

Dùng khi không biết trước số lần lặp, chỉ biết điều kiện dừng.

**Cú pháp:**
```js
let count = 1;
while (count <= 5) {
  console.log(count);
  count++;
}
```

---

### Vòng lặp do...while

Dùng khi muốn đảm bảo code trong vòng lặp được thực hiện ít nhất 1 lần, dù điều kiện có đúng hay không.

**Cú pháp:**
```js
let num = 1;
do {
  console.log(num);
  num++;
} while (num <= 5);
```

---

### Vòng lặp for...of và for...in

- **for...of**: Lặp qua các giá trị của một mảng, chuỗi, hoặc đối tượng có thể lặp lại.
- **for...in**: Lặp qua các thuộc tính (key) của một object.

**Ví dụ for...of:**
```js
let arr = [10, 20, 30];
for (let value of arr) {
  console.log(value); // 10, 20, 30
}
```

**Ví dụ for...in:**
```js
let obj = {a: 1, b: 2, c: 3};
for (let key in obj) {
  console.log(key, obj[key]); // a 1, b 2, c 3
}
```

---

### Bài tập luyện tập vòng lặp

1. Dùng vòng lặp for, in ra các số chẵn từ 2 đến 10.
2. Dùng vòng lặp while, in ra các số lẻ từ 1 đến 9.
3. Dùng vòng lặp for...of, in ra từng phần tử của mảng `['JS', 'Python', 'Java']`.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị biến để kiểm tra kết quả.

--- 

## Object (Đối tượng) trong JavaScript

### Khai báo và truy cập Object

Object là kiểu dữ liệu quan trọng giúp lưu trữ dữ liệu có cấu trúc phức tạp hơn mảng.

**Khai báo:**
```js
let person = {
  name: "Nam",
  age: 22,
  isStudent: true
};
```

**Truy cập thuộc tính:**
```js
console.log(person.name);      // "Nam"
console.log(person["age"]);    // 22
```
- Có thể truy cập thuộc tính bằng dấu chấm (`.`) hoặc dấu ngoặc vuông (`[]`).

---

### Thêm, sửa, xóa thuộc tính

**Thêm thuộc tính:**
```js
person.gender = "male";        // Thêm thuộc tính mới
```
**Sửa giá trị thuộc tính:**
```js
person.age = 23;               // Sửa giá trị thuộc tính
```
**Xóa thuộc tính:**
```js
delete person.isStudent;       // Xóa thuộc tính
```

---

### Duyệt qua các thuộc tính của Object

**for...in:**
```js
for (let key in person) {
  console.log(key, person[key]);
}
```
- `for...in` giúp lặp qua tất cả các key của object.

**Object.keys, Object.values, Object.entries:**
```js
console.log(Object.keys(person));   // ["name", "age", "gender"]
console.log(Object.values(person)); // ["Nam", 23, "male"]
console.log(Object.entries(person)); // [["name", "Nam"], ["age", 23], ["gender", "male"]]
```

---

### Một số thao tác thường gặp với Object

- **Kiểm tra thuộc tính:**
```js
if ("name" in person) {
  console.log("Có thuộc tính name");
}
```
- **Gộp object:**
```js
let obj1 = {a: 1};
let obj2 = {b: 2};
let merged = {...obj1, ...obj2}; // {a: 1, b: 2}
```
- **Sao chép object:**
```js
let copy = {...person};
```

---

### Bài tập luyện tập Object

1. Tạo một object lưu thông tin một cuốn sách gồm: `title`, `author`, `year`.
2. Thêm thuộc tính `genre` cho object trên.
3. Duyệt qua tất cả các thuộc tính và in ra theo dạng: `key: value`.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị thuộc tính để kiểm tra kết quả.

--- 

## String (Chuỗi) trong JavaScript

### Khai báo và truy cập ký tự

**Ví dụ:**
```js
let str = "Hello, World!";
console.log(str[0]); // "H"
console.log(str[1]); // "e"
console.log(str[2]); // "l"
console.log(str[3]); // "l"
console.log(str[4]); // "o"
console.log(str[5]); // ","
console.log(str[6]); // " "
console.log(str[7]); // "W"
console.log(str[8]); // "o"
console.log(str[9]); // "r"
console.log(str[10]); // "l"
console.log(str[11]); // "d"
console.log(str[12]); // "!"
```

### Một số phương thức chuỗi hay dùng

**Ví dụ:**
```js
let str = "Hello, World!";
console.log(str.length); // 13
console.log(str.toUpperCase()); // "HELLO, WORLD!"
console.log(str.toLowerCase()); // "hello, world!"
console.log(str.includes("World")); // true
console.log(str.indexOf("World")); // 7
console.log(str.slice(7, 12)); // "World"
console.log(str.split(", ")); // ["Hello", "World!"]
console.log(str.replace("World", "JavaScript")); // "Hello, JavaScript!"
```

### Bài tập luyện tập

1. Tạo một chuỗi `sentence` và in ra từng ký tự của chuỗi bằng vòng lặp for.
2. Tạo một chuỗi `sentence` và in ra từng ký tự của chuỗi bằng vòng lặp for...of.
3. Tạo một chuỗi `sentence` và in ra từng ký tự của chuỗi bằng vòng lặp for...in.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị chuỗi để kiểm tra kết quả.

--- 

## Cấu trúc dữ liệu nâng cao

### Set

**Ví dụ:**
```js
let set = new Set([1, 2, 3]);
console.log(set.size); // 3
set.add(4);
console.log(set.has(4)); // true
set.delete(2);
console.log(set.has(2)); // false
```

### Map

**Ví dụ:**
```js
let map = new Map([["name", "Nam"], ["age", 25]]);
console.log(map.size); // 2
console.log(map.get("name")); // "Nam"
map.set("address", "Hà Nội");
console.log(map.has("address")); // true
map.delete("age");
console.log(map.has("age")); // false
```

### Stack

**Ví dụ:**
```js
let stack = [];
stack.push(1);
stack.push(2);
console.log(stack.pop()); // 2
console.log(stack.pop()); // 1
```

### Queue

**Ví dụ:**
```js
let queue = [];
queue.push(1);
queue.push(2);
console.log(queue.shift()); // 1
console.log(queue.shift()); // 2
```

### Bài tập luyện tập

1. Tạo một đối tượng `person` với các thuộc tính `name`, `age`, `isStudent`.
2. Thêm thuộc tính `address` vào đối tượng `person`.
3. Xóa thuộc tính `isStudent` khỏi đối tượng `person`.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị thuộc tính để kiểm tra kết quả.

--- 

## Linked List (Danh sách liên kết)

### Khái niệm và cài đặt

**Ví dụ:**
```js
function Node(value) {
  this.value = value;
  this.next = null;
}

function LinkedList() {
  this.head = null;
}

LinkedList.prototype.add = function(value) {
  let newNode = new Node(value);
  if (!this.head) {
    this.head = newNode;
  } else {
    let current = this.head;
    while (current.next) {
      current = current.next;
    }
    current.next = newNode;
  }
};

LinkedList.prototype.remove = function(value) {
  if (!this.head) return;
  if (this.head.value === value) {
    this.head = this.head.next;
    return;
  }
  let current = this.head;
  while (current.next) {
    if (current.next.value === value) {
      current.next = current.next.next;
      return;
    }
    current = current.next;
  }
};

LinkedList.prototype.print = function() {
  let current = this.head;
  while (current) {
    console.log(current.value);
    current = current.next;
  }
};
```

### Duyệt, thêm, xóa node

**Ví dụ:**
```js
let list = new LinkedList();
list.add(1);
list.add(2);
list.add(3);
list.print(); // 1, 2, 3
list.remove(2);
list.print(); // 1, 3
```

### Bài tập luyện tập

1. Tạo một danh sách liên kết với các giá trị 1, 2, 3, 4, 5.
2. Thêm giá trị 6 vào cuối danh sách.
3. Xóa giá trị 3 khỏi danh sách.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị các node để kiểm tra kết quả.

--- 

## Tree (Cây nhị phân)

### Khái niệm và cài đặt

**Ví dụ:**
```js
function Node(value) {
  this.value = value;
  this.left = null;
  this.right = null;
}

function BinaryTree() {
  this.root = null;
}

BinaryTree.prototype.insert = function(value) {
  let newNode = new Node(value);
  if (!this.root) {
    this.root = newNode;
  } else {
    let current = this.root;
    while (true) {
      if (value < current.value) {
        if (!current.left) {
          current.left = newNode;
          break;
        }
        current = current.left;
      } else {
        if (!current.right) {
          current.right = newNode;
          break;
        }
        current = current.right;
      }
    }
  }
};

BinaryTree.prototype.search = function(value) {
  let current = this.root;
  while (current) {
    if (value === current.value) {
      return true;
    } else if (value < current.value) {
      current = current.left;
    } else {
      current = current.right;
    }
  }
  return false;
};

BinaryTree.prototype.traverse = function() {
  let result = [];
  let current = this.root;
  let stack = [];
  while (current || stack.length > 0) {
    while (current) {
      stack.push(current);
      current = current.left;
    }
    current = stack.pop();
    result.push(current.value);
    current = current.right;
  }
  return result;
};
```

### Duyệt cây

**Ví dụ:**
```js
let tree = new BinaryTree();
tree.insert(5);
tree.insert(3);
tree.insert(7);
console.log(tree.traverse()); // [3, 5, 7]
```

### Bài tập luyện tập

1. Tạo một cây nhị phân với các giá trị 5, 3, 7, 2, 4, 6, 8.
2. Duyệt cây theo thứ tự trái, gốc, phải.
3. Duyệt cây theo thứ tự gốc, trái, phải.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi cấu trúc cây để kiểm tra kết quả.

--- 

## Graph (Đồ thị)

### Khái niệm và biểu diễn

**Ví dụ:**
```js
let graph = {
  A: ["B", "C"],
  B: ["A", "D"],
  C: ["A", "D"],
  D: ["B", "C"]
};
```

### Thuật toán duyệt đồ thị (BFS, DFS)

**Ví dụ:**
```js
function bfs(graph, start) {
  let queue = [start];
  let visited = new Set();
  while (queue.length > 0) {
    let node = queue.shift();
    if (!visited.has(node)) {
      visited.add(node);
      console.log(node);
      for (let neighbor of graph[node]) {
        queue.push(neighbor);
      }
    }
  }
}

function dfs(graph, start) {
  let stack = [start];
  let visited = new Set();
  while (stack.length > 0) {
    let node = stack.pop();
    if (!visited.has(node)) {
      visited.add(node);
      console.log(node);
      for (let neighbor of graph[node]) {
        stack.push(neighbor);
      }
    }
  }
}

bfs(graph, "A"); // A, B, C, D
dfs(graph, "A"); // A, C, D, B
```

### Bài tập luyện tập

1. Tạo một đồ thị với các đỉnh A, B, C, D và các cạnh AB, AC, AD, BD, CD.
2. Duyệt đồ thị bằng thuật toán BFS và DFS.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi cấu trúc đồ thị để kiểm tra kết quả.

--- 

## Thuật toán tìm kiếm và sắp xếp cơ bản

### Tìm kiếm tuyến tính, nhị phân

**Ví dụ:**
```js
let arr = [1, 2, 3, 4, 5];
console.log(linearSearch(arr, 3)); // 2
console.log(binarySearch(arr, 3)); // 2
```

### Các thuật toán sắp xếp

**Ví dụ:**
```js
let arr = [5, 3, 8, 4, 2];
console.log(bubbleSort(arr)); // [2, 3, 4, 5, 8]
console.log(selectionSort(arr)); // [2, 3, 4, 5, 8]
console.log(insertionSort(arr)); // [2, 3, 4, 5, 8]
console.log(mergeSort(arr)); // [2, 3, 4, 5, 8]
console.log(quickSort(arr)); // [2, 3, 4, 5, 8]
```

### Bài tập luyện tập

1. Tạo một mảng số nguyên, sắp xếp mảng đó bằng các thuật toán sắp xếp đã học.
2. Tạo một mảng số nguyên, tìm kiếm giá trị 3 trong mảng bằng cả hai thuật toán tìm kiếm.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị mảng để kiểm tra kết quả.

--- 

## Thuật toán nâng cao: DP, Backtracking, Greedy

### Dynamic Programming

**Ví dụ:**
```js
function fibonacci(n) {
  if (n <= 1) return n;
  let dp = [0, 1];
  for (let i = 2; i <= n; i++) {
    dp[i] = dp[i - 1] + dp[i - 2];
  }
  return dp[n];
}

console.log(fibonacci(10)); // 55
```

### Backtracking

**Ví dụ:**
```js
function permute(arr) {
  let result = [];
  function backtrack(path) {
    if (path.length === arr.length) {
      result.push(path);
      return;
    }
    for (let i = 0; i < arr.length; i++) {
      if (!path.includes(arr[i])) {
        backtrack(path.concat(arr[i]));
      }
    }
  }
  backtrack([]);
  return result;
}

console.log(permute([1, 2, 3])); // [[1, 2, 3], [1, 3, 2], [2, 1, 3], [2, 3, 1], [3, 1, 2], [3, 2, 1]]
```

### Greedy Algorithm

**Ví dụ:**
```js
function coinChange(coins, amount) {
  let count = 0;
  let i = coins.length - 1;
  while (amount > 0 && i >= 0) {
    if (amount >= coins[i]) {
      amount -= coins[i];
      count++;
    } else {
      i--;
    }
  }
  return amount === 0 ? count : -1;
}

console.log(coinChange([1, 2, 5], 11)); // 3
```

### Bài tập luyện tập

1. Tìm cách đổi 1000 đồng thành các tờ tiền 1000, 2000, 5000, 10000, 20000, 50000, 100000, 200000, 500000 đồng bằng thuật toán Greedy.
2. Tìm cách đổi 1000 đồng thành các tờ tiền 1000, 2000, 5000, 10000, 20000, 50000, 100000, 200000, 500000 đồng bằng thuật toán Dynamic Programming.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị amount để kiểm tra kết quả.

--- 

## Kỹ thuật Two Pointers và Sliding Window

### Two Pointers

**Ví dụ:**
```js
let arr = [1, 2, 3, 4, 5];
let left = 0;
let right = arr.length - 1;
while (left < right) {
  console.log(arr[left] + arr[right]);
  left++;
  right--;
}
```

### Sliding Window

**Ví dụ:**
```js
let str = "abcabcbb";
let maxLength = 0;
let charSet = new Set();
let left = 0;
for (let right = 0; right < str.length; right++) {
  while (charSet.has(str[right])) {
    charSet.delete(str[left]);
    left++;
  }
  charSet.add(str[right]);
  maxLength = Math.max(maxLength, right - left + 1);
}
console.log(maxLength); // 3
```

### Bài tập luyện tập

1. Tạo một mảng số nguyên, tìm hai số có tổng bằng 10 bằng kỹ thuật Two Pointers.
2. Tạo một chuỗi, tìm độ dài của chuỗi con không có ký tự lặp lại bằng kỹ thuật Sliding Window.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị mảng hoặc chuỗi để kiểm tra kết quả.

--- 

## Bit Manipulation (Xử lý bit)

### Các phép toán bit cơ bản

**Ví dụ:**
```js
let a = 5; // 0101
let b = 3; // 0011
console.log(a & b); // 1 (AND)
console.log(a | b); // 7 (OR)
console.log(a ^ b); // 6 (XOR)
console.log(~a);    // -6 (NOT)
console.log(a << 1); // 10 (LEFT SHIFT)
console.log(a >> 1); // 2 (RIGHT SHIFT)
console.log(a >>> 1); // 2 (UNSIGNED RIGHT SHIFT)
```

### Ứng dụng phổ biến

**Ví dụ:**
```js
function isEven(n) {
  return (n & 1) === 0;
}

console.log(isEven(4)); // true
console.log(isEven(5)); // false
```

### Bài tập luyện tập

1. Tạo một mảng số nguyên, kiểm tra tính chẵn lẻ của từng phần tử bằng phép toán bit.
2. Tạo một mảng số nguyên, kiểm tra tính chẵn lẻ của từng phần tử bằng phép toán bit.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị mảng để kiểm tra kết quả.

--- 

## Đệ quy nâng cao

### Đệ quy trên cấu trúc dữ liệu

**Ví dụ:**
```js
function sum(arr) {
  if (arr.length === 0) return 0;
  return arr[0] + sum(arr.slice(1));
}

console.log(sum([1, 2, 3, 4, 5])); // 15
```

### Đệ quy với memoization

**Ví dụ:**
```js
function fibonacci(n, memo = {}) {
  if (n <= 1) return n;
  if (memo[n]) return memo[n];
  memo[n] = fibonacci(n - 1, memo) + fibonacci(n - 2, memo);
  return memo[n];
}

console.log(fibonacci(10)); // 55
```

### Bài tập luyện tập

1. Tạo một đối tượng `person` với các thuộc tính `name`, `age`, `isStudent`.
2. Thêm thuộc tính `address` vào đối tượng `person`.
3. Xóa thuộc tính `isStudent` khỏi đối tượng `person`.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi giá trị thuộc tính để kiểm tra kết quả.

--- 

## Đánh giá độ phức tạp thuật toán và Big O

### Big O Notation

**Ví dụ:**
```js
function linearSearch(arr, target) {
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] === target) return i;
  }
  return -1;
}

console.log(linearSearch([1, 2, 3, 4, 5], 3)); // 2
```

### Time & Space Complexity

**Ví dụ:**
```js
function fibonacci(n) {
  if (n <= 1) return n;
  let dp = [0, 1];
  for (let i = 2; i <= n; i++) {
    dp[i] = dp[i - 1] + dp[i - 2];
  }
  return dp[n];
}

console.log(fibonacci(10)); // 55
```

### Bảng so sánh

**Ví dụ:**
```js
let arr = [1, 2, 3, 4, 5];
console.log(linearSearch(arr, 3)); // 2
console.log(binarySearch(arr, 3)); // 2
```

--- 

## Trie, Heap, Priority Queue và Chủ đề nâng cao

### Trie

**Ví dụ:**
```js
let trie = new Trie();
trie.insert("apple");
trie.insert("banana");
console.log(trie.search("apple")); // true
console.log(trie.search("banana")); // true
console.log(trie.search("app")); // false
```

### Heap & Priority Queue

**Ví dụ:**
```js
let heap = new MaxHeap();
heap.insert(5);
heap.insert(3);
heap.insert(8);
console.log(heap.extractMax()); // 8
```

### Chủ đề LeetCode nâng cao

**Ví dụ:**
```js
let graph = {
  A: ["B", "C"],
  B: ["A", "D"],
  C: ["A", "D"],
  D: ["B", "C"]
};

function bfs(graph, start) {
  let queue = [start];
  let visited = new Set();
  while (queue.length > 0) {
    let node = queue.shift();
    if (!visited.has(node)) {
      visited.add(node);
      console.log(node);
      for (let neighbor of graph[node]) {
        queue.push(neighbor);
      }
    }
  }
}

bfs(graph, "A"); // A, B, C, D
```

### Bài tập luyện tập

1. Tạo một đồ thị với các đỉnh A, B, C, D và các cạnh AB, AC, AD, BD, CD.
2. Duyệt đồ thị bằng thuật toán BFS và DFS.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi cấu trúc đồ thị để kiểm tra kết quả.

--- 

## Dynamic Programming nâng cao: Bitmask DP

### Bitmask DP là gì?

**Ví dụ:**
```js
let n = 3;
let dp = Array(1 << n).fill(0);
console.log(dp); // [0, 0, 0, 0, 0, 0, 0, 0]
```

### Ứng dụng Bitmask DP

**Ví dụ:**
```js
let n = 3;
let dp = Array(1 << n).fill(0);
console.log(dp); // [0, 0, 0, 0, 0, 0, 0, 0]
```

### Bài tập luyện tập

1. Tạo một đồ thị với các đỉnh A, B, C, D và các cạnh AB, AC, AD, BD, CD.
2. Duyệt đồ thị bằng thuật toán BFS và DFS.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi cấu trúc đồ thị để kiểm tra kết quả.

--- 

## Advanced Graph Algorithms

### Dijkstra, Union-Find, Tarjan

**Ví dụ:**
```js
let graph = {
  A: ["B", "C"],
  B: ["A", "D"],
  C: ["A", "D"],
  D: ["B", "C"]
};

function dijkstra(graph, start) {
  let distances = {};
  let priorityQueue = new MinPriorityQueue();
  priorityQueue.enqueue(start, 0);
  distances[start] = 0;
  while (!priorityQueue.isEmpty()) {
    let { element: node, priority: dist } = priorityQueue.dequeue();
    if (dist > distances[node]) continue;
    for (let neighbor of graph[node]) {
      let newDist = dist + 1;
      if (newDist < distances[neighbor] || distances[neighbor] === undefined) {
        distances[neighbor] = newDist;
        priorityQueue.enqueue(neighbor, newDist);
      }
    }
  }
  return distances;
}

console.log(dijkstra(graph, "A")); // { A: 0, B: 1, C: 1, D: 2 }
```

### Segment Tree & Fenwick Tree

**Ví dụ:**
```js
let arr = [1, 2, 3, 4, 5];
function buildSegmentTree(arr, start, end) {
  if (start === end) return { sum: arr[start] };
  let mid = Math.floor((start + end) / 2);
  let left = buildSegmentTree(arr, start, mid);
  let right = buildSegmentTree(arr, mid + 1, end);
  return {
    sum: left.sum + right.sum,
    left: left,
    right: right
  };
}

function querySegmentTree(node, start, end, qStart, qEnd) {
  if (qStart <= start && end <= qEnd) return node.sum;
  if (end < qStart || qEnd < start) return 0;
  let mid = Math.floor((start + end) / 2);
  return querySegmentTree(node.left, start, mid, qStart, qEnd) + querySegmentTree(node.right, mid + 1, end, qStart, qEnd);
}

let segmentTree = buildSegmentTree(arr, 0, arr.length - 1);
console.log(querySegmentTree(segmentTree, 0, 4, 1, 3)); // 9
```

### Bài tập luyện tập

1. Tạo một đồ thị với các đỉnh A, B, C, D và các cạnh AB, AC, AD, BD, CD.
2. Duyệt đồ thị bằng thuật toán BFS và DFS.

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi cấu trúc đồ thị để kiểm tra kết quả.

--- 

## Lộ trình luyện LeetCode nâng cao & Kinh nghiệm thực chiến

**Ví dụ:**
```js
let graph = {
  A: ["B", "C"],
  B: ["A", "D"],
  C: ["A", "D"],
  D: ["B", "C"]
};

function bfs(graph, start) {
  let queue = [start];
  let visited = new Set();
  while (queue.length > 0) {
    let node = queue.shift();
    if (!visited.has(node)) {
      visited.add(node);
      console.log(node);
      for (let neighbor of graph[node]) {
        queue.push(neighbor);
      }
    }
  }
}

bfs(graph, "A"); // A, B, C, D
```

**Gợi ý:**
- Hãy tự thử viết code cho từng bài tập, thay đổi cấu trúc đồ thị để kiểm tra kết quả.

--- 
