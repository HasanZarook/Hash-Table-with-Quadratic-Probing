

# 🗂️ Hash Table with Quadratic Probing

## 🚀 Project Overview

This C++ project implements a **hash table** using **open addressing with quadratic probing**. It efficiently stores words and tracks collisions during insertion.

* 📦 **Stores words** from a file
* ⚡ **Uses quadratic probing** to resolve collisions
* 📊 **Tracks probes and collisions** for each insertion
* 🔍 **Supports search** to find words and report probe counts

This project is perfect for learning **hashing, collision resolution, and C++ OOP**.

---

## 🛠️ Features

* 💻 **Insertion with quadratic probing**
* 📈 **Collision counting** for each insertion
* 🔢 **Probe statistics**: average probes, total probes, number of failures
* 🔎 **Search functionality**: reports the number of probes to find a word
* 📝 **File-based input/output**: read word list and save probe stats

---

## 📁 Project Structure

```
HashTableProject/
├─ main.cpp           # Driver program with hash table implementation
├─ engmix.txt         # Input file containing words to insert
├─ statusL.txt        # Output file recording collisions/probes per word
└─ README.md          # Project documentation
```

---

## 📝 How to Run

1. Clone the repository:

   ```bash
   git clone <repo-url>
   ```
2. Compile the project:

   ```bash
   g++ main.cpp -o hashTableApp
   ```
3. Run the program:

   ```bash
   ./hashTableApp
   ```
4. Input the word to search when prompted:

   ```
   Enter the word to find
   example
   ```

---

## 📊 Example Output

```
apple -> inserted
banana -> inserted
grape -> inserted
Average probes/insert = 1.3 = 13/10, size = 10, failures = 0
Enter the word to find
banana
your word is exist, No. of probes to find the word is :2
```

---

## 💡 Key Concepts

* **Quadratic Probing**: `(hash(key) + j^2) % tableSize` for collision resolution
* **ASCII Hashing**: Sum of ASCII values of characters in a word
* **Open Addressing**: Handles collisions without linked lists
* **Probe Tracking**: Counts the number of probes for insertion and search

---

## 🎯 Future Improvements

* ✅ Support dynamic resizing when load factor exceeds a threshold
* ✅ Implement **linear probing** as an alternative method
* ✅ Add deletion and rehashing support
* ✅ Enhance file input/output for large datasets

---

## 👨‍💻 Author

**Hasan Zarook** – Computer Engineering, 2021-CE-58

---

## 🔖 License

This project is licensed under **MIT License** – see the LICENSE file for details.

---

Do you want me to make that version too?
