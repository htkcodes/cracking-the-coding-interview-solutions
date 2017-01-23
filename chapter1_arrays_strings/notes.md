<ol><b>Hash Tables</b></ol>
<li>maps keys to values for highly efficient lookup</li>
<li>in a very simple implementation, has an underlying array and a hash function</li>
<li>hash function maps the key to an integer, indicating the index in the array. The object is then stored at the index</li>
<li>1. Make the array small and store objects in a linked list at index hash(key) % array_length OR</li>
<li>2. implement the hash table with a BST (guarantee an O(log n) lookup time if tree balanced and may use less space because a larger array is no longer needed in the very beginning</li>

<ol><b>ArrayList</b></ol>
<li>dynamically resizing array providing O(1) access</li>
<li>typical implementation: when array is full, the array doubles in size</li>
<li>each doubling takes O(n) time, but happens so rarely that its amortized time is still O(1)</li>

<ol><b>StringBuffer</b></ol>
<li>helps avoid inc. big O for copying characters</li>
<li>simply creates an array of all strings, copying them back to a string only when necessary</li>

