# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
student_data1 = {
    'ID': [1, 2, 3, 4],
    'Name': ['Alice', 'Bob', 'Charlie', 'David'],
    'Grade': ['A', 'B', 'C', 'B']
}
df1 = pd.DataFrame(student_data1)
student_data2 = {
    'ID': [5, 6, 7, 8],
    'Name': ['Eva', 'Frank', 'Grace', 'Hannah'],
    'Grade': ['A', 'C', 'B', 'A']
}
df2 = pd.DataFrame(student_data2)
combined_df = pd.concat([df1, df2], axis=0)
print("Row-wise Concatenated DataFrame:")
print(combined_df)
```

## Output
<img width="1387" height="658" alt="image" src="https://github.com/user-attachments/assets/12a7458b-0f80-4209-a061-9ffdb9b8cd0f" />


## Result
The code is executed successfully.
