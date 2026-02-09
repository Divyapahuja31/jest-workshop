# Jest Workshop Submission

## Student Details
- Name: Divya Pahuja
- Roll Number: 2024-B-24052005A
- GitHub Username: https://github.com/Divyapahuja31

---

## Tests Written

List each test you wrote and briefly explain **what bug or regression it prevents**.

### 1. Test Name: no coupon case
**What it protects against:**  
Verifies that standard purchases without any discount codes are calculated correctly, ensuring the base pricing logic is solid.

---

### 2. Test Name: SAVE10 coupon
**What it protects against:**  
Confirms that the "SAVE10" coupon correctly applies a 10% discount, ensuring customers receive the promised savings.

---

### 3. Test Name: FLAT50 boundary case
**What it protects against:**  
Prevents the total amount from becoming negative when a flat discount (like 50) exceeds the subtotal, avoiding scenarios where the system might owe the customer money.

---

### 4. Test Name: invalid subtotal throws error
**What it protects against:**  
Ensures the function rejects invalid inputs (like negative numbers) to prevent incorrect financial calculations and potential system errors.

---

### 5. Test Name: case-insensitive coupon
**What it protects against:**  
Ensures that coupon codes are accepted regardless of letter casing (e.g., "save10" works just like "SAVE10"), improving the user experience.

---

## CI Pipeline (if implemented)
- Did CI pass successfully? Yes (Verified locally with `npm test`, setup in `.github/workflows/ci.yml`)
- GitHub Actions Run URL: (Please push to GitHub to generate this URL)

---

## Reflection (1–2 lines)
What is **one thing** you understood better about testing or CI after this workshop?
I learned how to automate testing using GitHub Actions, ensuring that every code change is verified before merging, which improves code reliability.
