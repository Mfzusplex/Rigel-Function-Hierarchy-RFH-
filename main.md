Rigel Function Hierarchy

Devised in November 2025 using a mix of autoiterative subcubic graph functions, the fast-growing hierarchy, arrays, and even the Busy Beaver function, the Rigel hierarchy was created to express numbers that grow faster than those defined by the traditional fast-growing hierarchy.
Each level of the Rigel hierarchy represents a new order of growth obtained by repeatedly applying a previous-level function to itself.

1. Formal Definition

Let rigelₙ denote the n-th member of the Rigel hierarchy.
Using the notation f⁽ᵏ⁾(x) to represent the k-fold self-composition of f on x, we define:

rigel₀(x) = fgh[x](scg[x](x))
rigelₙ₊₁(x) = (rigelₙ)^[rigelₙ(x)](x)
rigel*ₙ₊₁(x) = BB((rigelₙ)^[rigelₙ(x)](x))


where BB(k) denotes the Busy Beaver function.

2. Interpretation

rigel₀(x) defines the base layer using the internal iterative operators fgh and scg.
These act as generalized transformations representing arithmetic or combinatorial growth.

rigel₁(x) corresponds to rigel₀ applied to itself rigel₀(x) times:

rigel₁(x) = rigel₀^[rigel₀(x)](x)


rigelₙ(x) extends this recursion, producing a hierarchy similar to the fast-growing hierarchy but defined in terms of self-application depth rather than ordinal indices.

The accelerated variant rigel*ₙ(x) incorporates the Busy Beaver function, surpassing all computable growth rates.

3. Growth Overview
Function	Definition	Relative Growth	Domain
rigel₀(x)	fghx
	Computable but large	Recursive
rigel₁(x)	rigel₀^rigel₀(x)
	Hyper-recursive	Computable
rigel₂(x)	rigel₁^rigel₁(x)
	Beyond FGH	Sub-recursive
rigel*ₙ(x)	BB((rigelₙ)^rigelₙ(x)
)	Non-computable	Trans-recursive

4. References

W. Ackermann — Zum Hilbertschen Aufbau der reellen Zahlen, Mathematische Annalen, 99(1):118–133, 1928

A. Grzegorczyk — Some classes of recursive functions, Rozprawy Matematyczne, 4:1–45, 1953

T. Rado — On non-computable functions, Bell System Technical Journal, 41(3):877–884, 1962

L. Kirby, J. Paris — Accessible independence results for Peano arithmetic, Bull. London Math. Soc., 14(4):285–293, 1982

S. Aaronson — Who Can Name the Bigger Number? (1999)

E. W. Weisstein — Fast-Growing Function, MathWorld – Wolfram Web Resource

Googology Wiki Community — Exploring large-number notations and hierarchies, Googology Wiki, 2025

R. M. Solovay — Notes on fast-growing hierarchies and ordinal functions, Unpublished manuscript, 1985
