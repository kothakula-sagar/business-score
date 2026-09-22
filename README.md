# Business Score

## Beginner Documentation

Business Score turns employee review answers into percentages from **0% to 100%**. You do not need to calculate anything manually.

### 1. Add departments
Open **Manage** and create your departments.

### 2. Add employees
Add employees under the correct department.

### 3. Choose a review period
The system supports **Weekly, Monthly, Quarterly, Half-yearly and Yearly** reviews.

### 4. Answer review questions
Each question has three choices:
- **Yes = 100% of that question**
- **Partially = 50% of that question**
- **No = 0% of that question**

### 5. Employee score
For example, with 10 answered questions:

`7 Yes + 2 Partially + 1 No`

`((7 × 1) + (2 × 0.5)) ÷ 10 × 100 = 80%`

The employee therefore receives **80%**.

### 6. Department score
The department score is the average of the reviewed employees in that department.

### 7. Overall business score
The overall business score is the average of departments that have review data. Departments with no review data are shown as **No data**, rather than being counted as 0%.

### 8. Score bands
| Score | Label |
|---|---|
| 85–100% | Excellent |
| 70–84.99% | Good |
| 50–69.99% | Average |
| 0–49.99% | Needs improvement |

### 9. Dashboard
The Dashboard shows the overall score, department scores, employee counts, rankings and filters.

### 10. Data backup
The app stores data in browser localStorage. Use **Export JSON** regularly for backup. Use **Import JSON** to restore an exported backup. **Reset all** clears the current browser data.

The application also contains a **📖 How It Works** tab with this beginner-friendly explanation inside the app.
