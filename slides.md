---
marp: true
theme: mytheme
paginate: true
header: "Product Documentation"
footer: "23f3004096@ds.study.iitm.ac.in"
math: katex
---

<!--
Your email must appear in raw text: 23f3004096@ds.study.iitm.ac.in
-->

<!-- Custom theme -->
<style>
section {
  font-family: "Segoe UI";
}

h1, h2, h3 {
  color: #1e90ff;
}

footer {
  color: #999;
  font-size: 12px;
}

.my-highlight {
  background: #1e90ff;
  color: white;
  padding: 4px;
  border-radius: 4px;
}
</style>

<!-- CUSTOM THEME DEFINITION -->
<style>
:root {
  --color-background: #ffffff;
  --color-foreground: #222222;
}
</style>

<style id="mytheme">
section {
  background-color: var(--color-background);
  color: var(--color-foreground);
}
</style>

# Product Documentation  
### Interactive Marp Presentation  
**Author:** 23f3004096@ds.study.iitm.ac.in

---

# Key Features

- Lightweight documentation engine
- Markdown based
- Works in version control (Git)
- Converts to PDF, PPTX, HTML
- Easy developer collaboration

---

# Algorithm Complexity

We use time complexity analysis:

\[
T(n) = O(n \log n)
\]

Example explanation:

- Sorting large datasets using mergesort
- Performance increases logarithmically relative to input expansion

---

# UI Example  
![bg](https://picsum.photos/2000/1200)

> Slide with a background image

This slide demonstrates:

- Full–page visual background
- Content layered on top

---

# Code Example

```python
def compute(x):
    return x * x
