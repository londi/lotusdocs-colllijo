---
weight: 230
title: "Latex"
description: ""
icon: "article"
date: "2024-10-24T10:57:43+02:00"
lastmod: "2024-10-24T10:57:43+02:00"
katex: true
draft: false
toc: true
---

{{% alert context="info" %}}

Damit die Mathematischen Gleichungen angezeigt werden muss in der `frontmatter`
der Siete, welche die Latex Gleichungen enthält die Eigenschaft `katex: true`
gesetzt werden.

{{% /alert %}}

Mit diesem Theme ist es mögliche mathematische Gleichungen mittels Latex Syntax
zu schreiben. Dafür wird das `katex` Shortcode verwendet. Hier einige Beispiele:

{{< katex >}}
 
$$ 1+1 $$

{{< /katex >}}

---

{{< katex >}}
 
$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

{{< /katex >}}
 
---

{{< katex >}}
 
$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$

{{< /katex >}}

---

{{< katex >}}
 
$$
E = mc^2
$$

{{< /katex >}}

---

{{< katex >}}
 
$$
\int_{a}^{b} f(x) \, dx = F(b) - F(a)
$$

{{< /katex >}}

---

{{< katex >}}
 
$$
e^{i\pi} + 1 = 0
$$

{{< /katex >}}

---

{{< katex >}}
 
$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

{{< /katex >}}

---

{{< katex >}}
 
$$
\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e
$$

{{< /katex >}}
