# go-blockchain
A simple blockchain program illustrated with golang where users create a book with title, author, published date and ISBN number. The book is then checked out by 
writing to a block the created book id (created after the book has been created), the user that checked out and the check out date which will then successfully create a block
a new block. A series of created blocks forms a blockchain which also contains a hash (a unique keyword) and a previous hash (except for the genesis block)
