[![author](https://img.shields.io/badge/author-mohd--faizy-red)](https://github.com/mohd-faizy)
![made-with-Markdown](https://img.shields.io/badge/Made%20with-markdown-blue)
![Language](https://img.shields.io/github/languages/top/mohd-faizy/Learn_Matplotlib)
![Maintained](https://img.shields.io/maintenance/yes/2024)
![Last Commit](https://img.shields.io/github/last-commit/mohd-faizy/Learn_Matplotlib)
[![contributions welcome](https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square)](https://github.com/mohd-faizy/Learn_Matplotlib)
![Size](https://img.shields.io/github/repo-size/mohd-faizy/Learn_Matplotlib)

# Matplotlib

![Matplotlib-banner](https://github.com/mohd-faizy/Learn_Matplotlib/blob/main/_img/matplotlib-banner.jpg)

Welcome to the Matplotlib repository! This repo is dedicated to providing helpful resources, tutorials, and examples for using the Matplotlib library in Python.

## Table of Contents

- [Matplotlib](#matplotlib)
  - [Table of Contents](#table-of-contents)
  - [Roadmap](#roadmap)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Basic Plot](#basic-plot)
    - [Subplots](#subplots)
    - [Customizing Plots](#customizing-plots)
    - [3D Plotting](#3d-plotting)
  - [Features](#features)


## Roadmap

![Matplotlib-roadmap](https://github.com/mohd-faizy/Learn_Matplotlib/blob/main/_img/Matplotlib-Roadmap.png)

## Introduction

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. It provides an object-oriented API for embedding plots into applications.

This repository aims to help users of all skill levels to better understand and utilize the Matplotlib library through comprehensive guides, code snippets, and example projects.

## Installation

To install Matplotlib, you can use pip, the Python package installer. Ensure you have Python installed, then run:

```bash
pip install matplotlib
```

For more detailed installation instructions, please refer to the [official Matplotlib installation guide](https://matplotlib.org/stable/users/installing.html).

## Usage

Here are some basic examples to get you started with Matplotlib:

### Basic Plot

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 25, 30, 35]

plt.plot(x, y)
plt.title('Basic Plot')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

### Subplots

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y1 = [10, 20, 25, 30, 35]
y2 = [15, 25, 20, 30, 40]

fig, axs = plt.subplots(2)

axs[0].plot(x, y1, 'r')
axs[0].set_title('First Subplot')
axs[1].plot(x, y2, 'b')
axs[1].set_title('Second Subplot')

plt.tight_layout()
plt.show()
```

### Customizing Plots

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 25, 30, 35]

plt.plot(x, y, marker='o', linestyle='--', color='g', label='Line with Markers')
plt.title('Customized Plot')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.legend()
plt.grid(True)
plt.show()
```

### 3D Plotting

```python
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D
import numpy as np

fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')

x = np.linspace(-5, 5, 100)
y = np.linspace(-5, 5, 100)
X, Y = np.meshgrid(x, y)
Z = np.sin(np.sqrt(X**2 + Y**2))

ax.plot_surface(X, Y, Z, cmap='viridis')

plt.title('3D Surface Plot')
plt.show()
```

For more examples and detailed tutorials, please refer to the [official Matplotlib documentation](https://matplotlib.org/stable/contents.html).

## Features

- Comprehensive library for creating static, animated, and interactive visualizations
- Object-oriented API for embedding plots
- Support for a wide range of plots and visualizations
- Customization capabilities for plots

## ⚖ ➤ License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## ❤️ Support

If you find this repository helpful, show your support by starring it! For questions or feedback, reach out on [Twitter(`X`)](https://twitter.com/F4izy).

#### $\color{skyblue}{\textbf{Connect with me:}}$

➤ If you have questions or feedback, feel free to reach out!!!

[<img align="left" src="https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/twitter_circle-512.png" width="32px"/>][twitter]
[<img align="left" src="https://cdn-icons-png.flaticon.com/512/145/145807.png" width="32px"/>][linkedin]
[<img align="left" src="https://cdn-icons-png.flaticon.com/512/2626/2626299.png" width="32px"/>][Portfolio]

[twitter]: https://twitter.com/F4izy
[linkedin]: https://www.linkedin.com/in/mohd-faizy/
[Portfolio]: https://ai.stackexchange.com/users/36737/faizy?tab=profile

---

<img src="https://github-readme-stats.vercel.app/api?username=mohd-faizy&show_icons=true" width=380px height=200px />
