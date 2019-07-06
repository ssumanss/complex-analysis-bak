# Taylor's Theorem

This thorem says that any analytic function in a circular domain has a power series expansion.

!!! success "Taylor's Thorem"
     Let $\Omega$ be an open connected set and let $a\in \Omega$. Let $f:\Omega→\mathbb{C}$ be analytic on $\Omega$. Then there exists an $r>0$ such that
     $$f(z)=\sum_{n=0}^\infty \dfrac{f^{(n)}(a)}{n!}(z−a)^n; \quad z ∈ D(a,r).$$
     In other words, the Taylor series of $f$ at $a$ converges uniformly and absolutely to $f$ for all $z∈D(a,r)$.


```python
print("Hello World!")
```

```sequence
Title: Example sequence diagram
A->B: Sync call
B-->A: Sync return
A->C: Another sync call
C->>D: Async call
D-->>C: Async return
```

```flow
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...

st->op1->cond
cond(yes)->io->e
cond(no)->sub1(right)->op1
```
