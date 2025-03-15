### Tugas2
### 1. Temp Convert

#### Deskripsi Fungsi
Fungsi ini mengonversi suhu dari Fahrenheit ke Celsius menggunakan rumus konversi yang tepat.

#### Input
- `fahrenheit`: Suhu dalam derajat Fahrenheit (number).

#### Output
- Mengembalikan suhu dalam derajat Celsius (number).

### Contoh
```javascript
const inputFahrenheit = 32; // Input: 32°F
const celsius = fahrenheitToCelsius(inputFahrenheit); // Output: 0°C
```

---


### 2. Length Covert 

#### Deskripsi Fungsi
Fungsi ini mengonversi panjang dari centimeter ke kilometer dan sebaliknya.

#### Input
- `value`: Panjang dalam centimeter atau kilometer (number).

#### Output
- Mengembalikan string yang merepresentasikan panjang dalam kilometer atau centimeter.

### Contoh
```javascript
console.log(convertLength(100000)); // Output: "1 km"
console.log(convertLength(1));      // Output: "100000 cm"
```
### 3. Ood Check 
#### Deskripsi Fungsi
Fungsi ini memeriksa apakah suatu bilangan integer adalah genap.

#### Input
- `n`: Bilangan yang akan diuji (number).

#### Output
- Mengembalikan boolean `true` jika genap, dan `false` jika ganjil.

### Contoh
```javascript
console.log(isEven(1000)); // Output: true
console.log(isEven(1001)); // Output: false
### 4. Remove String 

#### Deskripsi Fungsi
Fungsi ini menghapus kemunculan pertama dari string pencarian dalam string input.

#### Input
- `inputString`: String asli (string).
- `searchString`: String yang ingin dihapus (string).

#### Output
- Mengembalikan string baru dengan kemunculan pertama dari `searchString` dihapus.

### Contoh
```javascript
const result = removeFirstOccurrence("Hello world", "ell"); // Output: "Ho world"

### 5. Palindrome Check 

#### Deskripsi Fungsi
Fungsi ini memeriksa apakah sebuah string adalah palindrom (dibaca sama dari depan dan belakang).

#### Input
- `str`: String yang akan diperiksa (string).

#### Output
- Mengembalikan boolean `true` jika string tersebut adalah palindrom, dan `false` jika tidak.

### Contoh
```javascript
const inputString = "madam"; 
const result = isPalindrome(inputString); // Output: true
```
