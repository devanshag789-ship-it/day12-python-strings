# #DAY 12 — STRINGS IN PYTHON

---

## 1. Introduction to Strings

A **string** is a sequence of characters used to store text data in Python.

Strings can be  written inside single quotes `' '` or double quotes `" "`, no matter how you define it.

Strings are one of the most commonly used data types because programs often work with names, number, messages, and text.

### Basic Example

```python
name="Devansh"
favNo='9'
day="Sunday"
print("Hello,",name)
print("My favourite number is",favNo)
```

---

## 2. Defining Strings

In Python, strings can be defined in multiple ways.

### Using Double Quotes

```python
msg="Hello Python"
```

### Using Single Quotes

```python
msg='Hello Python'
```

Both methods work the same. Choose one based on readability.

### Writing Quotes Inside a String

Sometimes we want to write sentences that already contain quotes, for example:

👉 `hello, "today I am at Tajmahal"`

### Using Escape Character `\`

If you want to use the **same quotes inside**, add a backslash `\`.

```python
text="hello,\"today I am at tajmahal\""
print(text)
```

Python allows this by using **different outer quotes**.

### Using Double Quotes Inside Single Quotes

```python
text='hello, "today I am at tajmahal"'
print(text)
```

---

### Using Single Quotes Inside Double Quotes

```python
text="hello, 'today I am at tajmahal'"
print(text)
```

---

---

## 3. Multiline Strings

Multiline strings allow text to span across multiple lines.

They are created using triple quotes.

### Triple Double Quotes

```python
para="""Python is easy.
Python is powerful.
Python is popular."""
```

### Triple Single Quotes

```python
note='''Line one
Line two
Line three'''
```

Multiline strings are useful for:

- Paragraph text
- Documentation
- Long messages
- Printing Chat

---

## 4. String Indexing

Strings are **ordered**, meaning each character has a position called an index.

In Python, Indexing always starts from **0**.

Example:

```python
word="Python"
	print(word[0])
print(word[1])
```

Output:

```python
P
y
```

### Index Positions

```python
P   y   t   h   o   n
0   1   2   3   4   5
```

---

## 5. Looping Through a String

We can use a **for loop** to print every character one by one.

### Basic Loop

```python
text="Python"

for ch in text:
print(ch)
```

Output:

```python
P
y
t
h
o
n
```

---

## 6. Important Characteristics of Strings

1. Strings are **immutable** — characters cannot be changed directly.
2. Strings are ordered sequences.
3. Indexing helps access individual characters.

Example :

```python
text="Hello"
# text[0] = "Y"   ❌ Not allowed
```

---

## ✅One-Line Concept

> Strings in Python are ordered, immutable sequences of characters that support indexing to access individual elements.
>
