---
id: 5900f40f1000cf542c50ff22
title: 'Завдання 163: заштриховані трикутники'
challengeType: 1
forumTopicId: 301797
dashedName: problem-163-cross-hatched-triangles
---

# --description--

Розглянемо рівносторонній трикутник, у якому проведені меридіани, як у трикутнику розміру 1 на рисунку нижче.

<img alt="трикутники розміру 1 і розміру 2" src="https://cdn.freecodecamp.org/curriculum/project-euler/cross-hatched-triangles.gif" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Тепер у цьому трикутнику можна знайти шістнадцять трикутників різної форми, розміру, напряму чи розташування. Використовуючи трикутники розміру 1 як будівельні блоки, можна сформувати більші трикутники, такі як трикутник розміру 2 на рисунку вище. Тепер у трикутнику розміру 2 можна знайти сто чотири трикутники різної форми, розміру, напряму чи розташування.

Можна помітити, що трикутник розміру 2 складається з 4 будівельних блоків трикутника розміру 1. Трикутник розміру 3 складатиметься з 9 будівельних блоків трикутника розміру 1, а трикутник розміру $n$ складатиметься з $n^2$ будівельних блоків трикутника розміру 1.

Якщо позначити $T(n)$ як кількість трикутників, що містяться в трикутнику розміру $n$, тоді

$$\begin{align}   & T(1) = 16 \\\\
  & T(2) = 104 \end{align}$$

Знайдіть $T(36)$.

# --hints--

`crossHatchedTriangles()` має повернути `343047`.

```js
assert.strictEqual(crossHatchedTriangles(), 343047);
```

# --seed--

## --seed-contents--

```js
function crossHatchedTriangles() {

  return true;
}

crossHatchedTriangles();
```

# --solutions--

```js
// solution required
```
