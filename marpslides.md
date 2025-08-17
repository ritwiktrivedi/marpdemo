---
marp: true
theme: custom
paginate: true
size: 16:9
class: lead
---

<!-- Custom theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
  color: #222;
}
section.lead h1 {
  font-size: 2.8em;
  color: #1e88e5;
}
footer {
  font-size: 0.7em;
  color: #666;
  text-align: right;
}
section::after {
  content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 10px;
  right: 20px;
  font-size: 0.65em;
  color: #444;
}
</style>

# 📘 Product Documentation with Marp  
*Author: Technical Writer @ Software Co.*  
**Email:** 22f1000120@ds.study.iitm.ac.in  

---

# Why Marp?

- Write presentations in **Markdown**
- Easy to maintain in **version control (Git)**
- Convert to:
  - PDF
  - HTML
  - PowerPoint
- Enables **custom themes** and styling

---

# Custom Styling

With Marp directives and CSS overrides, you can:

- 🎨 Define custom themes  
- 🖼️ Add background images  
- 🔢 Use mathematical notation  
- 📑 Automatically generate page numbers  

---

<!-- background image slide -->
![bg](https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=1200&q=80)

# Visual Impact

Background images can be set per slide using:  
```markdown
![bg](path/to/image.jpg)
