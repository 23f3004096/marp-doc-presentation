---
marp: true
theme: custom-theme
paginate: true
math: mathjax
style: |
  @import 'default';
  
  section.custom-theme {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
  }
  
  section.custom-theme h1 {
    color: #ffd700;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
  }
  
  section.custom-theme h2 {
    color: #87ceeb;
  }
  
  footer {
    font-size: 14px;
    color: #666;
  }
  
  section.image-bg {
    background-image: url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=1200');
    background-size: cover;
    color: white;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
  }
---

<!-- _class: custom-theme -->

# Product Documentation Guide
## Software Engineering Best Practices

**Presented by:** Technical Writing Team
**Contact:** 23f3004096@ds.study.iitm.ac.in

---

<!-- _class: custom-theme -->

## Overview

This presentation covers:
- Documentation standards
- Version control workflow
- Performance considerations
- Best practices for technical writers

---

<!-- _class: image-bg -->

## Why Documentation Matters

> "Code tells you how, documentation tells you why."

- Reduces onboarding time
- Improves code maintainability
- Facilitates team collaboration
- Serves as a knowledge base

---

## Algorithmic Complexity in Documentation Tools

When choosing documentation tools, consider performance:

**Time Complexity for Search:**
$$O(\log n)$$ - Binary search in indexed docs

**Space Complexity for Version Control:**
$$O(n)$$ - Linear storage per version

**Build Time Complexity:**
$$T(n) = O(n \cdot k)$$

Where:
- $n$ = number of documentation files
- $k$ = average file processing time

---

## Version Control Best Practices

### Branching Strategy
```
main
├── develop
│   ├── feature/api-docs
│   └── feature/user-guide
└── release/v1.0
```

**Key Principles:**
- Commit early and often
- Write descriptive commit messages
- Use pull requests for review
- Tag releases appropriately

---

## Markdown Benefits for Technical Docs

| Feature | Benefit |
|---------|---------|
| Plain Text | Easy version control |
| Simple Syntax | Quick to learn |
| Portable | Works everywhere |
| Extensible | Supports plugins |

**Formula for Documentation ROI:**

$$\text{ROI} = \frac{\text{Time Saved} - \text{Time Invested}}{\text{Time Invested}} \times 100\%$$

---

## Custom Styling Example

### Code Documentation Format
```python
def calculate_complexity(n: int) -> int:
    """
    Calculate time complexity.
    
    Args:
        n: Input size
    
    Returns:
        Complexity value O(n log n)
    """
    return n * math.log(n)
```

---

<!-- _class: custom-theme -->

## Contact & Resources

**Questions?**

📧 Email: 23f3004096@ds.study.iitm.ac.in
📚 GitHub: [Your Repository]
📖 Documentation: [Your Docs Site]

---

## Thank You!

**Remember:** Good documentation is like a good joke - if you have to explain it, it's not that good.

*Keep your docs clear, concise, and current!*

---
```

For example:
```
https://raw.githubusercontent.com/johnsmith/marp-presentation/main/slides.md
