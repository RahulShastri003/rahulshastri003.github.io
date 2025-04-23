---
layout: default
---

### Peer-reviewed Writing

1. Dephasing enabled fast charging of quantum batteries, Rahul Shastri, Chao
Jiang, Guo-Hua Xu, B. Prasanna Venkatesh, and Gentaro Watanabe, ([npj Quantum Information 11,9 (2025)](https://www.nature.com/articles/s41534-025-00959-5) )
2. Controlling Work Output and Coherence in Finite Time Quantum Otto
Engines Through Monitoring, Rahul Shastri and B. Prasanna Venkatesh ( [Phys. Rev. E 109, 014102 (2024)](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.109.014102))
3. Optimization of asymmetric quantum Otto engine cycles, Rahul Shastri and
B. Prasanna Venkatesh ([Phys. Rev. E 106, 024123 (2022)](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.106.024123) )

<div id="articles">

  <h3>Blog</h3>
  <ul>
    {% for post in site.categories.Blog %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>

  <h3>Setup Notes</h3>
  <ul>
    {% for post in site.categories.Setup-Notes %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>

</div>

---
