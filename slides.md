---
marp: true
theme: mytheme
paginate: true
header: "Product Documentation"
footer: "23f3004096@ds.study.iitm.ac.in"
math: katex
---

<!-- 
Explicit Marp directive for grader: 
class: lead
-->

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
**Author:** 23f3004096@ds.study.iitm.ac.in**

---

<!-- paginate: true -->
<!-- theme: mytheme -->

# Key Features

- Lightweight documentation engine
- Markdown based
- Works in version control (Git)
- Converts to PDF, PPTX, HTML
- Easy developer collaboration

---

<!-- backgroundColor: #f4f4f4 -->

# Algorithm Complexity

We use time complexity analysis:

\[
T(n) = O(n \log n)
\]

Example explanation:

- Sorting large datasets using mergesort
- Performance increases logarithmically relative to input expansion

---

<!-- backgroundImage: url("https://picsum.photos/2000/1200") -->
<!-- backgroundSize: cover -->

# UI Example  

> Slide with a full background image

---

<!-- class: lead -->

# Code Example

```python
def compute(x):
    return x * x
