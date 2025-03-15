# Checkpoint Algorithms and its elements

1. **Initialization:**

   - The code initializes three variables: `vowelCount`, `wordCount`, and `charCount`. These are used to track the count of vowels, words, and characters, respectively.

2. **Input Handling:**

   - It prompts the user to input a sentence, which is stored in the `sentence` variable.

3. **Main Loop:**

   - A `REPEAT` loop is used to iterate over each character in the sentence.
   - **Word Count**: Every time a space (`" "`) is encountered, `wordCount` is incremented by 1.
   - **Vowel Count**: Each time a character that is a vowel (i.e., `a, e, i, o, u, y`) is found, `vowelCount` is incremented by 1.

4. **Termination:**

   - The loop continues until it encounters a period (`"."`), signaling the end of the sentence.

5. **Output:**
   - The program prints the total number of characters, words, and vowels.

---

### **License Example:**

You can include a simple `LICENSE` file with the MIT License:

```plaintext
MIT License

Copyright (c) 2025 mrfinndev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
