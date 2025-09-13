# Sample Datasets for Model Evaluation

## Student Code Sample Categories

### Beginner Level Samples (Syntax and Basic Logic Errors)

**Sample 1: Loop Index Error**
```python
# Student attempting to print list elements
numbers = [1, 2, 3, 4, 5]
for i in range(len(numbers)):
    print(numbers[i + 1])  # Off-by-one error

# Expected Learning Objective: Understanding list indexing and range bounds
# Misconception: Confusion about zero-based indexing
# Ideal Prompt: "What happens when i equals 4 in your loop?"
