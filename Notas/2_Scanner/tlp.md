# Subset construction (Conversion de DFA a NFA)

> Para todo NFA existe un DFA equivalente

Entoncs:
- Todo NFA ya es un DFA
- Todo NFA puede convertirse en un DFA equivalente

**Funcion de transicion DFA:**
La transicion de un DFA solo puede devolver un unico estado:
```
                    δ: Q × Σ → Q
```

**Funcion de transicion NFA:**
La transicion de un NFA puede devolver ningun estado, uno o varios al mismo tiempo:
```
                    δ: Q × Σ → 2^Q
```

