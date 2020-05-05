### [Binary](./binary_search.rs)

B-Trees are version of 2-3 trees, which are self-balancing. They are used to improve Disk reads and have a complexity of
O(log(n)), for every tree operations.The number of Childrens/Keys a particular node has, is
determined by the Branching Factor/Degree of that tree.
Btrees will always have sorted keys.

- Branching Factor(B) / Degree (D):
  If B = n, n <= Children per Node < 2(n), n-1 <= Keys per Node < 2(n) - 1

__Properties__
* Worst/Average case performance for all operations	O(log n)
* Space complexity	O(n)


