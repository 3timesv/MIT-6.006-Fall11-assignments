## 3.1 - Range Queries

**(a)** 4. AVL Trees

**(b)** 3. `O(log(n))`

**(c)** 3. `O(log(n))`

**(d)** 3. `O(log(n))`

**(e)** 6. `Rank(h) - Rank(l) + 1`

**(f)** 5. `Rank(h) - Rank(l)`

**(g)** 6. `Rank(h) - Rank(l) + 1`

**(h)** 5. `Rank(h) - Rank(l)`

**(i)** 4. the number of nodes in the sub-tree rooted at _node_

**(j)** 1. `O(1)`

**(k)** 2. 1

**(l)** 3. 3

**(m)** 4. 6

**(n)** 4. 10

**(o)** 1., 2., 3., 4., 5. INSERT, DELETE, ROTATE-LEFT, ROTATE-RIGHT, REBALANCE

**(p)** 3. `O(log(n))`

**(q)** 2. lowest common ancestor

**(r)** 3. `O(log(n))`

**(s)** 8. `O(log(n)) + O(L)`

**(t)** 8. `O(log(n)) + O(L)`

**(u)** 

Assume, _m_ is true answer and LCA returns _n_ and _m_ != _n_

**Case 1** _m_ = _root_;

lines 3 to 6 will not execute and LCA will return _root_, i.e _n_ = _root_. 

This means that LCA returns true answer i.e _m_ = _n_.

**Case 2** _m_ = _root.left_;

line 4 will assign _node_ to _root.left_. And we return to _Case 1_.

**Case 3** _m_ = _root.right_;

this case is symmetric to _Case 2_.


