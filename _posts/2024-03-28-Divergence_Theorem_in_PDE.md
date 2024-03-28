---
layout: article
title: Divergence Theorem in PDE-PDE
tags: 
"last_modified_at:": 2024-03-28 13:55
share: "true"
---


The theorem is as below
# Theorem 1 (Divergence Theorem).

$$
\int _{\partial \Omega} \vec{F} \cdot \vec{n} \, dS =\int _{\Omega} div(\vec{F}) \, dV 
$$



- $div \cdot = \nabla \cdot$
*While used in PDE, it is often the format below*
# Corollary 1.

*Let $u\in C^2$, we have $\nabla u$ exists,then*
$$
\int _{\partial \Omega} \nabla u \cdot n\, dS =\int _{\Omega} \Delta u \, dV 
$$
*and it has a equal format*
$$
\int _{\partial \Omega}  \frac{\partial u}{\partial n}\, dS =\int _{\Omega} \Delta u \, dV 
$$

And another common format
# Corollary 2. 
 *Let $u,v \in C^2$, and we have $F=w\nabla u$ exists, then*
$$
\int _{\partial \Omega}w \nabla u \cdot n \, dS = \int _{\Omega}div(w \nabla u) \, dV =\int _{\Omega} \nabla w\nabla u+w \Delta u \, dV 
$$
*which is* 
$$
\int_{\partial \Omega} w \frac{\partial u}{\partial n} \, dS =\int _{\Omega} \nabla w \nabla u+w \Delta u \, dV 
$$
 *And more we have **Green First Formula***
$$
\int _{\Omega}w \Delta u \, dV =\int _{\partial \Omega}w  \frac{\partial u}{\partial n} \, dS - \int _{\Omega}\nabla w \nabla u \, dV 
$$



And based on Cor2, if we just change the order of w and u and we get
# Corollary3.
$$
\int _{\partial \Omega}w\frac{\partial u}{\partial n} - u\frac{\partial w}{\partial n} \, dS = \int _{\Omega}w\Delta u-u\Delta w \, dV
$$
*And we also call it **Green Second Formula***



