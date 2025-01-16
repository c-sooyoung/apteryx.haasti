---
marp: true
style: |-
  section {
    justify-content: start;
  }

  section.title {
    justify-content: center;
  }

  h1 {
    color: black;
  }

  img[alt~="center"] {
    display: block;
    margin: 0 auto;  
  }

paginate: true
math: mathjax
---
<!-- _class: title -->
<!-- _paginate: false -->

# Marp template

Sooyoung Cheong
Last updated 2024.11.04.

---

## Style settings explanation

- Content slides are top-aligned
  `justify-content: start;`

- Heading 1 is solid black

- `center` class for images

- Pagination is enabled

---

## Images

![center h:450](./rabbit.png)

<!-- _footer: The White Rabbit from _Alice's adventures in Wonderland_ (1865), illustration by John Tenniel, retrieved from [wikimedia commons](https://commons.wikimedia.org/wiki/File:Alice-white-rabbit.jpg). -->

---

## Equations

Difference map algorithm using the hybrid input-output method:

$$
\Psi^{(n+1)} = \Psi^{(n)}
+ \beta \left[ 
\Pi_F \left(\Pi_O (\Psi^{(n)}) + \frac{1}{\beta}(\Pi_O(\Psi^{(n)}) - \Psi^{(n)}) \right) -
\Pi_O \left( \Pi_F (\Psi^{(n)}) - \frac{1}{\beta}(\Pi_F(\Psi^{(n)}) - \Psi^{(n)}) \right)
\right]
$$

#### 

a boxed equation:

<div style="border: solid 1.5px black; padding: 30px 0 20px 0;">

$$
\Psi^{(n+1)} = \Psi^{(n)}
+ \Pi_F (2\Pi_O (\Psi^{(n)}) - \Psi^{(n)} )
- \Pi_O (\Psi^{(n)})
$$

</div>

<!-- _footer: Thibault, P. et al, (2008) Supplementary Material <br> Thibault, P. et al, (2009) -->

---

## Some symbols

single right arrow: &rarr;

double right arrow: &rArr;

brackets: &gt; &lt; &ge; &le;

