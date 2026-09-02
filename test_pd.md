import pandas as pd
# Define data as a Python dictionary
data = {
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [25, 30, 35],
    "City": ["New York", "London", "Paris"]
}

# Convert dictionary into a pandas DataFrame
df = pd.DataFrame(data)

print(df)