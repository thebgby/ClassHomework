### Python Questions: Comprehensive Topics

1. **Numbers:**

   - Write a Python function `is_prime(n)` that returns `True` if the number `n` is a prime number, and `False` otherwise.
   - Write a Python function `fibonacci(n)` that returns the `n`-th Fibonacci number.
   - Write a Python function `gcd(a, b)` that calculates the greatest common divisor of `a` and `b`.

2. **Operators:**

   - Write a Python function `evaluate_expression(expr)` that takes a mathematical expression in the form of a string (e.g., `"3 + 5 * 2"`) and returns the result.
   - Write a Python function `bitwise_operations(a, b)` that takes two integers and performs bitwise AND, OR, and XOR operations.
   - Write a Python function `is_bit_shifted_correctly(n, shift)` that returns `True` if `n` shifted left by `shift` produces the expected result.

3. **Booleans:**

   - Write a Python function `boolean_operations(a, b)` that performs `and`, `or`, and `not` operations on two boolean values.
   - Write a Python function `is_palindrome(s)` that returns `True` if a string `s` is a palindrome, and `False` otherwise.
   - Write a Python function `find_all_trues(lst)` that returns the indices of all `True` values in a list of boolean values.

4. **Strings:**

   - Write a Python function `reverse_string(s)` that returns the string reversed.
   - Write a Python function `count_vowels(s)` that counts the number of vowels in a string.
   - Write a Python function `find_substring(s, sub)` that returns the index of the first occurrence of a substring `sub` in a string `s`.

5. **Lists:**

   - Write a Python function `remove_duplicates(lst)` that removes duplicates from a list while preserving the order.
   - Write a Python function `sum_elements(lst)` that returns the sum of all elements in a list of numbers.
   - Write a Python function `reverse_list(lst)` that reverses a list.

6. **Tuples:**

   - Write a Python function `concatenate_tuples(t1, t2)` that concatenates two tuples.
   - Write a Python function `tuple_to_dict(t)` that converts a tuple of (key, value) pairs into a dictionary.
   - Write a Python function `find_max_tuple(lst)` that returns the tuple with the maximum first value from a list of tuples.

7. **Dictionaries:**

   - Write a Python function `merge_dicts(d1, d2)` that merges two dictionaries into one.
   - Write a Python function `filter_dict_by_value(d, threshold)` that returns a new dictionary where values greater than a `threshold` are filtered out.
   - Write a Python function `get_value_by_key(d, key)` that returns the value for a specific key in a dictionary.

8. **Loops:**

   - Write a Python function `count_vowels_in_sentence(sentence)` that uses a loop to count the number of vowels in a sentence.
   - Write a Python function `generate_multiples(n, count)` that generates and returns a list of `count` multiples of `n`.
   - Write a Python function `sum_numbers_until_zero(lst)` that sums the numbers in a list until a zero is encountered.

9. **List Comprehensions:**

   - Write a Python function `square_numbers(lst)` that returns a list of squares of numbers in a list using list comprehensions.
   - Write a Python function `filter_odd_numbers(lst)` that returns a list of odd numbers from a list using list comprehensions.
   - Write a Python function `string_lengths(lst)` that returns a list of lengths of strings in a list using list comprehensions.

10. **Conditionals:**

    - Write a Python function `grade(score)` that takes a test score and returns a grade based on the following scheme:
      - A: 90-100
      - B: 80-89
      - C: 70-79
      - D: 60-69
      - F: 0-59

11. **File Handling:**

    - Write a Python function `read_file(filename)` that reads a file and returns its content.
    - Write a Python function `write_to_file(filename, content)` that writes content to a specified file.

12. **JSON:**

    - Write a Python function `parse_json(json_string)` that takes a JSON string and returns the corresponding Python object.
    - Write a Python script that reads a JSON file and prints out specific fields from it.

13. **Regex:**

    - Write a Python function `extract_emails(text)` that takes a string `text` and returns a list of all the email addresses found within the string.
    - Write a Python script that uses regex to identify and replace all occurrences of non-alphanumeric characters in a string with an underscore.

14. **Functions:**

    - Write a Python function `is_armstrong_number(n)` that returns `True` if the number `n` is an Armstrong number, and `False` otherwise.
    - Write a Python function `factorial(n)` that returns the factorial of a given number `n`.

15. **Recursion:**

    - Write a recursive function `fibonacci(n)` that returns the `n`-th Fibonacci number.
    - Write a recursive function `sum_of_numbers(n)` that calculates the sum of the first `n` natural numbers.

16. **Lambda Functions:**

    - Write a lambda function that takes two arguments and returns their product. Assign this function to a variable named `multiply`.

17. **Object-Oriented Programming:**

    - Write a Python class `Rectangle` with attributes `width` and `height`. Include a method `area()` that returns the area of the rectangle.
    - Write a Python class `Square` that inherits from the `Rectangle` class. Add an `__init__` method that takes one argument `side` and initializes both `width` and `height` with this value.

18. **Modules:**

    - Write a module named `math_utils.py` that includes a function `is_prime(n)` which returns `True` if `n` is a prime number and `False` otherwise. Import and use this module in another script.

19. **Date and Time:**

    - Write a Python function `calculate_age(birthdate)` that takes a birthdate string in the format `YYYY-MM-DD` and returns the age in years.
    - Write a Python script to find the current day of the week.

20. **Decorators:**
    - Write a decorator `timing_decorator` that measures the time a function takes to execute. Apply this decorator to a function `slow_function()` which sleeps for 2 seconds before returning a message "Finished".

### Python Pandas Puzzle Questions

1. **DataFrame Creation:**

   - Create a Pandas DataFrame from a dictionary where the keys are column names and the values are lists of data. The DataFrame should represent a table with sample data.

2. **Data Filtering:**

   - Using an existing DataFrame, write a function `filter_data(df, column, value)` that filters the DataFrame based on a specific value in a given column.

3. **Data Transformation:**

   - Write a function `normalize_column(df, column)` that normalizes the values in a given column of a DataFrame using min-max scaling.

4. **Group by and Aggregate:**

   - Using a DataFrame, write a function `average_by_group(df, group_col, agg_col)` that computes the average of a specified column, grouped by another column.

5. **Join DataFrames:**
   - Write a function `join_dataframes(df1, df2, on)` that joins two Pandas DataFrames based on a common column, using an appropriate join type.

### Python Questions

1. **Datetime:**

   - Write a Python function `calculate_age(birthdate)` that takes a birthdate string in the format `YYYY-MM-DD` and returns the age in years.

2. **Datetime:**

   - Write a Python script to find the current day of the week.

3. **Regex:**

   - Write a Python function `extract_emails(text)` that takes a string `text` and returns a list of all the email addresses found within the string.

4. **Regex:**

   - Write a Python script that uses regex to identify and replace all occurrences of non-alphanumeric characters in a string with an underscore.

5. **JSON:**

   - Write a Python function `parse_json(json_string)` that takes a JSON string and returns the corresponding Python object.

6. **JSON:**

   - Write a Python script that reads a JSON file and prints out specific fields from it.

7. **Requests:**

   - Write a Python function `make_request(url, params)` that makes a GET request to a given URL with optional query parameters and returns the response.

8. **Requests:**

   - Write a Python script that sends a POST request to a URL with JSON data and prints out the server's response.

9. **Databases:**

   - Write a Python script that connects to a SQL database and executes a SELECT query to fetch data from a specific table.

10. **Databases:**
    - Write a Python script that inserts a new record into a database table.

### Python Questions using NumPy

1. **Array Creation:**

   - Write a Python function `create_random_array(size, low, high)` that generates and returns a NumPy array of `size` random integers between `low` and `high`.

2. **Array Operations:**

   - Write a Python function `calculate_statistics(arr)` that takes a NumPy array `arr` and returns the mean, median, and standard deviation.

3. **Indexing and Slicing:**

   - Write a Python function `get_odd_elements(arr)` that takes a NumPy array `arr` and returns a new array containing only the odd numbers.

4. **Boolean Indexing:**

   - Write a Python script that uses boolean indexing to filter out elements in a NumPy array that are greater than a given threshold.

5. **Linear Algebra:**
   - Write a Python function `matrix_multiplication(matrix1, matrix2)` that takes two NumPy 2D arrays (matrices) and returns the result of their matrix multiplication.

### Python Questions using Matplotlib

1. **Basic Plot:**

   - Write a Python function `plot_sine_wave()` that generates a plot of the sine wave from 0 to 2π using Matplotlib.

2. **Scatter Plot:**

   - Write a Python function `plot_scatter(x, y)` that generates a scatter plot from two lists of `x` and `y` coordinates.

3. **Bar Chart:**
   - Write a Python function `plot_bar_chart(labels, values)` that generates a bar chart using Matplotlib for the given `labels` and `values`.
