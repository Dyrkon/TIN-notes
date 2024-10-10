Necht’ L je bezkontextový jazyk. Pak existuje konstanta
 $\exists k > 0, k \in \mathbb{N}^{+}$ taková, že je-li:
$\forall z \in \Sigma^{*} : z \in L \; \land \mid z \mid \geq k$, pak lze $z$ napsat ve tvaru ($\Rightarrow$): 
$$
\begin{gather}
\exists u,v,w,x,y \in \Sigma^{*} : z = uvwxy \land vx \neq \varepsilon \\ \land \mid vwx \mid \leq k \land \forall i \in \mathbb{N} : i \geq 0 : uv^{i}wx^{i}y \in L
\end{gather}
$$