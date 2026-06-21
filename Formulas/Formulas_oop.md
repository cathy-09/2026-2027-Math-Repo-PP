# Справочни материали за ДЗИ по математика — Общообразователна подготовка

Справочник с формули за Държавен зрелостен изпит (ДЗИ) по математика.

## Съдържание

- [Квадратно уравнение](#квадратно-уравнение)
- [Квадратна функция](#квадратна-функция)
- [Корен, степен и логаритъм](#корен-степен-и-логаритъм)
- [Съединения без повторения](#съединения-на-n-елемента-от-k-ти-клас-без-повторения)
- [Прогресии](#прогресии)
- [Вероятности](#вероятности)
- [Статистика](#статистика)
- [Средни стойности](#средни-стойности-на-елементи-на-дадено-множество)
- [Зависимости в триъгълник и успоредник](#зависимости-в-триъгълник-и-успоредник-при-стандартни-означения)
- [Формули за лице](#формули-за-лице)
- [Тригонометрични функции — таблица](#тригонометрични-функции)
- [Тригонометрични тъждества](#тригонометрични-тъждества)
- [Ръбести и валчести тела](#ръбести-и-валчести-тела)

---

## Квадратно уравнение

$$ax^2 + bx + c = 0,\quad a \neq 0$$

$$D = b^2 - 4ac$$

$$x_{1,2} = \frac{-b \pm \sqrt{D}}{2a}, \quad \text{при } D \geq 0$$

$$ax^2 + bx + c = a(x - x_1)(x - x_2)$$

**Формули на Виет:**

$$x_1 + x_2 = -\frac{b}{a} \qquad x_1 \cdot x_2 = \frac{c}{a}$$

## Квадратна функция

Графиката на $y = ax^2 + bx + c$ е парабола с връх точката:

$$\left(-\frac{b}{2a},\ -\frac{D}{4a}\right)$$

## Корен, степен и логаритъм

$$\sqrt[2k]{a^2} = |a| \qquad \sqrt[2k+1]{a^{2k+1}} = a,\ k \in \mathbb{N}$$

$$a^{-m} = \frac{1}{a^m},\quad a \neq 0$$

$$a^{\frac{m}{n}} = \sqrt[n]{a^m}$$

$$\sqrt[n]{\sqrt[k]{a}} = \sqrt[nk]{a}$$

$$\sqrt[nk]{a^{mk}} = \sqrt[n]{a^m},\quad a > 0,\ k \geq 2,\ n \geq 2,\ m, n, k \in \mathbb{N}$$

Ако $a > 1$, то $a^x > a^y \Leftrightarrow x > y$; ако $0 < a < 1$, то $a^x < a^y \Leftrightarrow x > y$ (за $x, y \in \mathbb{R}$).

$$\log_a x = b \Leftrightarrow a^b = x$$

$$\log_a a^b = b \qquad a^{\log_a x} = x,\quad a, b > 0,\ a \neq 1$$

$$\log_a(xy) = \log_a x + \log_a y \qquad \log_a\frac{x}{y} = \log_a x - \log_a y$$

$$\log_a x^n = n \log_a x$$

$$\log_{a^m} x = \frac{1}{m}\log_a x,\quad m \neq 0$$

$$\log_a x = \frac{\log_b x}{\log_b a},\quad a \neq 1,\ a > 0,\ x, y > 0,\ b > 0,\ b \neq 1$$

## Съединения на n елемента от k-ти клас без повторения

$$P_n = n! = n(n-1)\cdots 3 \cdot 2 \cdot 1$$

$$V_n^k = n(n-1)\cdots(n-k+1)$$

$$C_n^k = \frac{V_n^k}{P_k} = \frac{n(n-1)\cdots(n-k+1)}{k(k-1)\cdots 3 \cdot 2 \cdot 1}$$

## Прогресии

**Аритметична прогресия:**

$$a_n = a_1 + (n-1)d$$

$$S_n = \frac{a_1 + a_n}{2}n = \frac{2a_1 + (n-1)d}{2}n$$

**Геометрична прогресия:**

$$a_n = a_1 \cdot q^{n-1}$$

$$S_n = a_1\frac{q^n - 1}{q - 1},\quad q \neq 1$$

**Формула за сложна лихва:**

$$K_n = K\left(1 + \frac{p}{100}\right)^n$$

---

## Вероятности

Вероятност за настъпване на събитието $A$:

$$P(A) = \frac{\text{брой на благоприятните изходи}}{\text{общ брой на изходите}}, \quad 0 \leq P(A) \leq 1$$

**Вероятност на сбор от събития:**

$$P(A \cup B) = P(A) + P(B),\quad A \text{ и } B \text{ са несъвместими}$$

$$P(A \cup B) = P(A) + P(B) - P(AB),\quad A \text{ и } B \text{ са съвместими}$$

**Вероятност на противоположно събитие:**

$$P(\overline{A}) = 1 - P(A),\quad \overline{A} \text{ е противоположно на събитието } A$$

**Условна вероятност:**

$$P(A \mid B) = \frac{P(AB)}{P(B)},\quad P(B) \neq 0$$

**Теорема за умножение на вероятности:**

$$P(AB) = P(A)\cdot P(B \mid A) = P(B)\cdot P(A \mid B),\quad P(A) \neq 0,\ P(B) \neq 0$$

**Формула на Бернули:**

$$P_n(k) = C_n^k \cdot p^k \cdot q^{n-k},\quad k = 0, 1, 2, \ldots, n$$

**Теорема за умножение на вероятности на независими събития:**

$$P(AB) = P(A)\cdot P(B)$$

Събитията $A$ и $B$ са независими, ако $P(A \mid B) = P(A)$.

## Статистика

**Средна аритметична стойност:**

$$\bar{x}_{\text{ар.}} = \frac{a_1 + a_2 + \cdots + a_n}{n},\quad n \in \mathbb{N}$$

**Претеглена средна стойност:**

$$\bar{x} = \frac{1}{n}\sum_{i=1}^{k} x_i n_i$$

където $n_i$ е относителна честота; $n$ — обем на извадката.

**Дисперсия:**

$$DX = E\left[(X - EX)^2\right]$$

## Средни стойности на елементи на дадено множество

**Средна геометрична стойност:**

$$\bar{x}_{\text{геом.}} = \sqrt[n]{a_1 \cdot a_2 \cdot a_3 \cdots a_n},\quad n \in \mathbb{N},\ a_i > 0$$

**Средна хармонична стойност:**

$$\bar{x}_{\text{харм.}} = \frac{n}{\dfrac{1}{a_1} + \dfrac{1}{a_2} + \cdots + \dfrac{1}{a_n}},\quad n \in \mathbb{N},\ a_i > 0$$

**Средна квадратична стойност:**

$$\bar{x}_{\text{квадр.}} = \sqrt{\frac{a_1^2 + a_2^2 + \cdots + a_n^2}{n}},\quad n \in \mathbb{N}$$

**Връзка между средните стойности:**

$$\frac{n}{\dfrac{1}{a_1}+\dfrac{1}{a_2}+\cdots+\dfrac{1}{a_n}} \leq \sqrt[n]{a_1 a_2 \cdots a_n} \leq \frac{a_1+a_2+\cdots+a_n}{n} \leq \sqrt{\frac{a_1^2+a_2^2+\cdots+a_n^2}{n}}$$

$$n \in \mathbb{N},\ a_i > 0$$

---

## Зависимости в триъгълник и успоредник при стандартни означения

**Правоъгълен триъгълник:**

$$c^2 = a^2 + b^2$$

$$S = \frac{1}{2}ab = \frac{1}{2}c\,h_c$$

$$a^2 = a_1 c \qquad b^2 = b_1 c \qquad h_c^2 = a_1 b_1$$

$$r = \frac{a + b - c}{2}$$

$$\sin\alpha = \frac{a}{c} \qquad \cos\alpha = \frac{b}{c} \qquad tg\,\alpha = \frac{a}{b} \qquad \cot g\,\alpha = \frac{b}{a}$$

**Произволен триъгълник:**

$$\frac{a}{\sin\alpha} = \frac{b}{\sin\beta} = \frac{c}{\sin\gamma} = 2R$$

$$a^2 = b^2 + c^2 - 2bc\cos\alpha$$

$$b^2 = a^2 + c^2 - 2ac\cos\beta$$

$$c^2 = a^2 + b^2 - 2ab\cos\gamma$$

**Формула за медиана:**

$$m_a^2 = \frac{1}{4}(2b^2 + 2c^2 - a^2)$$

$$m_b^2 = \frac{1}{4}(2a^2 + 2c^2 - b^2)$$

$$m_c^2 = \frac{1}{4}(2a^2 + 2b^2 - c^2)$$

**Формула за ъглополовяща:**

$$\frac{a}{b} = \frac{n}{m} \qquad l_c^2 = ab - mn$$

**Формула за диагоналите на успоредник:**

$$d_1^2 + d_2^2 = 2a^2 + 2b^2$$

## Формули за лице

**Триъгълник:**

$$S = \frac{1}{2}c\,h_c \qquad S = \frac{1}{2}ab\sin\gamma \qquad S = \sqrt{p(p-a)(p-b)(p-c)}$$

$$S = pr \qquad S = \frac{abc}{4R}$$

**Успоредник:**

$$S = a\,h_a \qquad S = ab\sin\alpha$$

**Трапец:**

$$S = \frac{a+b}{2}h$$

**Четириъгълник:**

$$S = \frac{1}{2}d_1 d_2 \sin\varphi,\quad \varphi - \text{ъгъл между диагоналите}$$

**Описан многоъгълник:**

$$S = pr$$

---

## Тригонометрични функции

| $\alpha^\circ$ | 0° | 30° | 45° | 60° | 90° | 120° | 135° | 150° | 180° | 270° | 360° |
|---|---|---|---|---|---|---|---|---|---|---|---|
| $\alpha$ rad | 0 | $\pi/6$ | $\pi/4$ | $\pi/3$ | $\pi/2$ | $2\pi/3$ | $3\pi/4$ | $5\pi/6$ | $\pi$ | $3\pi/2$ | $2\pi$ |
| $\sin\alpha$ | 0 | $1/2$ | $\sqrt2/2$ | $\sqrt3/2$ | 1 | $\sqrt3/2$ | $\sqrt2/2$ | $1/2$ | 0 | -1 | 0 |
| $\cos\alpha$ | 1 | $\sqrt3/2$ | $\sqrt2/2$ | $1/2$ | 0 | $-1/2$ | $-\sqrt2/2$ | $-\sqrt3/2$ | -1 | 0 | 1 |
| $tg\,\alpha$ | 0 | $\sqrt3/3$ | 1 | $\sqrt3$ | – | $-\sqrt3$ | -1 | $-\sqrt3/3$ | 0 | – | 0 |
| $\cot g\,\alpha$ | – | $\sqrt3$ | 1 | $\sqrt3/3$ | 0 | $-\sqrt3/3$ | -1 | $-\sqrt3$ | – | 0 | – |

## Тригонометрични тъждества

**Редукционни формули** ($90^\circ \pm \alpha$, $180^\circ \pm \alpha$, $270^\circ \pm \alpha$, $360^\circ \pm \alpha$): синус ↔ косинус, тангенс ↔ котангенс според квадранта (вж. оригиналната таблица в спецификацията).

**Основни тъждества:**

$$\sin^2\alpha + \cos^2\alpha = 1 \qquad tg\,\alpha \cdot \cot g\,\alpha = 1$$

**Формули за сбор/разлика на ъгли:**

$$\sin(\alpha \pm \beta) = \sin\alpha\cos\beta \pm \cos\alpha\sin\beta$$

$$\cos(\alpha \pm \beta) = \cos\alpha\cos\beta \mp \sin\alpha\sin\beta$$

$$tg(\alpha \pm \beta) = \frac{tg\,\alpha \pm tg\,\beta}{1 \mp tg\,\alpha\, tg\,\beta}$$

$$\cot g(\alpha \pm \beta) = \frac{\cot g\,\alpha\, \cot g\,\beta \mp 1}{\cot g\,\beta \pm \cot g\,\alpha}$$

**Формули за двоен ъгъл:**

$$\sin 2\alpha = 2\sin\alpha\cos\alpha$$

$$\cos 2\alpha = \cos^2\alpha - \sin^2\alpha = 2\cos^2\alpha - 1 = 1 - 2\sin^2\alpha$$

$$\sin 2\alpha = \frac{2tg\,\alpha}{1 + tg^2\alpha} \qquad \cos 2\alpha = \frac{1 - tg^2\alpha}{1 + tg^2\alpha}$$

$$tg\,2\alpha = \frac{2tg\,\alpha}{1 - tg^2\alpha} \qquad \cot g\,2\alpha = \frac{\cot g^2\alpha - 1}{2\cot g\,\alpha}$$

**Сума и разлика на синуси/косинуси:**

$$\sin\alpha + \sin\beta = 2\sin\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2}$$

$$\sin\alpha - \sin\beta = 2\cos\frac{\alpha+\beta}{2}\sin\frac{\alpha-\beta}{2}$$

$$\cos\alpha + \cos\beta = 2\cos\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2}$$

$$\cos\alpha - \cos\beta = -2\sin\frac{\alpha+\beta}{2}\sin\frac{\alpha-\beta}{2}$$

**Полуъгъл:**

$$1 - \cos 2\alpha = 2\sin^2\alpha \qquad 1 + \cos 2\alpha = 2\cos^2\alpha$$

**Произведение в сума:**

$$\sin\alpha\sin\beta = \frac{1}{2}\big(\cos(\alpha-\beta) - \cos(\alpha+\beta)\big)$$

$$\cos\alpha\cos\beta = \frac{1}{2}\big(\cos(\alpha-\beta) + \cos(\alpha+\beta)\big)$$

$$\sin\alpha\cos\beta = \frac{1}{2}\big(\sin(\alpha+\beta) + \sin(\alpha-\beta)\big)$$

---

## Ръбести и валчести тела

**Призма:**

$$S_{\text{л}} = Ph \qquad S = 2S_B + S_{\text{л}} \qquad V = Bh$$

**Пирамида:**

$$S_{\text{л}} = \frac{Pa}{2} \qquad S = S_B + S_{\text{л}} \qquad V = \frac{Bh}{3}$$

**Прав кръгов цилиндър:**

$$S_{\text{л}} = 2\pi r h \qquad S = 2\pi rh + 2\pi r^2 \qquad V = \pi r^2 h$$

**Прав кръгов конус:**

$$S_{\text{л}} = \pi r l \qquad S = \pi r l + \pi r^2 \qquad V = \frac{\pi r^2 h}{3}$$

**Сфера и кълбо:**

$$S = 4\pi r^2 \qquad V = \frac{4}{3}\pi r^3$$

---

