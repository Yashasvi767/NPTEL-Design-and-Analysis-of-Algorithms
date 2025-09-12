# Upper bounds, "big O"
- t(n) is said to be O(g(n)) if we can find suitable constants c and n₀ so that cg(n) is an upper bound for t(n) for n beyond n₀.
- t(n) <= cg(n) for every n>=n₀

<img width="739" height="557" alt="image" src="https://github.com/user-attachments/assets/605b4a37-95f0-45bc-9839-2468e3b12f10" />

## Big O example
- 100n + 5 is o(n<sup>2</sup>)
- <= 100n + n, for n>=5
- 101n <= 101n<sup>2</sup>, so n₀=5, c=101

  Alternatively,
- 100n + 5
- <= 100n + 5n, for n>=1
- = 105n <= 105n<sup>2</sup>, so n₀=1, c=105

- n₀ and c are not unique

Note:
- Useful properties
  1. If f1(n) is O(g1(n))
  2. If f2(n) is O(g2(n))
  then f1(n)+f2(n) is O(max(g1(n), g2(n)))

# Lower bounds, Ω (omega)
- t(n) is said to be Ω(g(n)) if we can find suitable constants c and n₀ so that cg(n) is an lower bound for t(n) for n beyond n₀

- t(n) >= cg(n), for every n>=n₀

<img width="704" height="533" alt="image" src="https://github.com/user-attachments/assets/55345d76-1a66-4ffa-8870-993951d88d24" />

# Tight bounds, θ (theta)
- t(n) is θ(g(n)) if it is both O(g(n)) and Ω(g(n))
- Find suitable constants c1, c2, and n₀, so that c2g(n)<=t(n)<=c1g(n) for every n>=n₀

 <img width="673" height="579" alt="image" src="https://github.com/user-attachments/assets/aa661767-3a80-4544-96fe-00485e1e2a36" />
