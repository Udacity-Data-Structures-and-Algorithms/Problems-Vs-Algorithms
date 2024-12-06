
## Problem 7: Request Routing in a Web Server with a Trie

### Explanation

The problem is to implement a web server that can route requests to the correct handler based on the request URL. The server implements the router using a trie data structure.  The trie is used to store the routes and the corresponding handlers.

### Time complexity

The time complexity of the trie data structure is O(L) where L is the length of the URL. The time complexity of the insert operation is O(L) and the time complexity of the search operation is also O(L).

### Space complexity

The space complexity of the trie data structure is O(N * L) where N is the number of routes and L is the length of the URL. The space complexity of the insert operation is O(L) and the space complexity of the search operation is also O(L).


