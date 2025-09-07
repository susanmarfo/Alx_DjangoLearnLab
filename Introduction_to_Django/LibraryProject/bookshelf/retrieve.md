# Get all books
>>> books = Book.objects.all()
>>> books
<QuerySet [<Book: 1984 by George Orwell (1949)>]>
>>> 

# Get a single book
>>> book = Book.objects.get(title="1984")
>>> book.title, book.author, book.publication_year
('1984', 'George Orwell', 1949)
>>> 
