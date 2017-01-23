<ol><b>Hash Tables</b></ol>
<li>maps keys to values for highly efficient lookup</li>
<li>in a very simple implementation, has an underlying array and a hash function</li>
<li>hash function maps the key to an integer, indicating the index in the array. The object is then stored at the index</li>
<li>1. Make the array small and store objects in a linked list at index hash(key) % array_length OR</li>
<li>2. implement the hash table with a BST (guarantee an O(log n) lookup time if tree balanced and may use less space because a larger array is no longer needed in the very beginning</li>
