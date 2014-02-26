% A Quick Introduction to Python
% Prepared by Assil Ksiksi
% March 2014

\newpage
\tableofcontents
\newpage

# What is Python?

* Object-oriented
* Dynamically typed
* General purpose (scientific, web development, mobile app dev, etc.)

# Section 0. Setting Up the Environment

### 1. Creating a Directory

Create a directory for the workshop. We'll be saving our work in this directory. An example could be `py-workshop` on the Desktop.

### 2. Checking if Python is Installed

1. Open up the Terminal (Unix) or Command Prompt (Windows).
2. Type `python --version`. Make sure the version returned is at least 2.5.
3. Navigate to the folder you just created via the command line. Use the `cd` command to do so.

### 3. The IPython Interpreter

After making sure you're in the directory you just created, type `ipython notebook` in your Terminal. This will start up the IPython notebook interface through your default web browser.

IPython is a special version of Python that adds a good amount of useful features to the Python interpreter. In addition, it comes with a Notebook version that allows you to interactively run your code in a web browser. Since Python is a dynamic language, you do not need to compile your code - simply type the code in a block and hit `Enter` to view the results live.

IPython also allows you to include images, text, and video along with your code. More details can be found in the IPython [documentation](http://ipython.org/ipython-doc/stable/interactive/notebook.html).

\newpage

# Section 1. Variables, Types, and User Input

```python
# Setup some variables of different types
a = 5
b = 12.0
c = 'apple'
d = True
e = [1, 5.0, False, 'orange']
f = {1: 'kiwi', 'banana': 3}

# Simple operations and access
print (a + 10) ** 2
print 'Value = %f' % (b * a)
print c + ' ' + c
print d
print e[1], e[-1]
print f['banana']

# Take user input
name = raw_input('Enter your name: ')
print 'Hello, %s!' % name
```

# Section 2. Flow Control and Looping

```python
# Simple if-elif-else block
if a < 5:
	print 'Less.'
elif a == 5:
	print 'Equal.'
else:
	print 'Greater.'

# Iterate over a range of numbers (1-10)
m = 10

for i in range(1, m+1):
	print i

# Iterate over a list
e.append('mango')
e.append(33.5)

for item in e:
	print e

# Simple while loop
i = 0

while i < 5:
	print 'Iteration: %d' % i
	i += 1
```