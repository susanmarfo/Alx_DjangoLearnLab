
book.title = "Nineteen Eighty-Four"
>>> book.save()
>>> 
>>> # Verify update
>>> book = Book.objects.get(author="George Orwell")
>>> book.title
'Nineteen Eighty-Four'
>>> 
