<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>

  <h1>n_sum</h1>

  <div>
    <a href="https://pypi.org/project/n-sum/" class="badge">
      <img src="https://img.shields.io/pypi/v/n-sum.svg" alt="PyPI Version">
    </a>
    <a href="https://pypi.org/project/n-sum/" class="badge">
      <img src="https://img.shields.io/pypi/pyversions/n-sum.svg" alt="Python Version">
    </a>
    <a href="https://github.com/shkumar5-india/n_sum/blob/main/LICENSE" class="badge">
      <img src="https://img.shields.io/pypi/l/n-sum.svg" alt="License">
    </a>
  </div>

  <p>A Python package for calculating sums of numbers and series. Provides functions for summing natural numbers, lists, squares, cubes, and arithmetic/geometric series.</p>

  <h2>Features</h2>
  <ul>
    <li><code>sum_n(n)</code> – Sum of first <code>n</code> natural numbers</li>
    <li><code>sum_list(numbers)</code> – Sum of a list of numbers</li>
    <li><code>sum_squares(n)</code> – Sum of squares of first <code>n</code> natural numbers</li>
    <li><code>sum_cubes(n)</code> – Sum of cubes of first <code>n</code> natural numbers</li>
    <li><code>arithmetic_series(a, d, n)</code> – Sum of first <code>n</code> terms of an arithmetic series</li>
    <li><code>geometric_series(a, r, n)</code> – Sum of first <code>n</code> terms of a geometric series</li>
  </ul>

  <h2>Installation</h2>

  <h3>From PyPI:</h3>
  <pre><code>pip install n-sum</code></pre>

  <h3>From TestPyPI (for testing):</h3>
  <pre><code>pip install -i https://test.pypi.org/simple/ n-sum</code></pre>

  <h2>Usage</h2>

  <pre><code>
from n_sum import sum_n, sum_list, sum_squares, sum_cubes, arithmetic_series, geometric_series

# Sum of first 10 natural numbers
print(sum_n(10))  # Output: 55

# Sum of a list
print(sum_list([1, 2, 3]))  # Output: 6

# Sum of squares
print(sum_squares(3))  # Output: 14

# Sum of cubes
print(sum_cubes(3))  # Output: 36

# Arithmetic series: first term=2, common difference=3, n=4
print(arithmetic_series(2, 3, 4))  # Output: 26

# Geometric series: first term=2, ratio=3, n=4
print(geometric_series(2, 3, 4))  # Output: 80
  </code></pre>

  <h2>Developer</h2>
  <p><strong>Hemanth Kumar Sirasapalli</strong><br>
  Email: <a href="mailto:sirasapalli1238@gmail.com">sirasapalli1238@gmail.com</a></p>

  <p>Source code and issues: <a href="https://github.com/shkumar5-india/n_sum">GitHub</a></p>

  <h2>License</h2>
  <p>This project is licensed under the <strong>MIT License</strong>. See the <a href="https://github.com/shkumar5-india/n_sum/blob/main/LICENSE">LICENSE</a> file for details.</p>

</body>
</html>
