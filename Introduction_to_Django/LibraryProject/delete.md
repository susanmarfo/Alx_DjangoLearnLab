book.delete()
(1, {'bookshelf.Book': 1})
>>> 
>>> # Verify deletion
>>> Book.objects.all()
<QuerySet []>
>>> 