# Project_3
Chinook SQL + pandas

This project connects to the Chinook sample SQLite database from a Jupyter notebook, runs a multi-table join to link customers → invoices → invoice lines → tracks → albums, and prints a tidy result: shows first 5 customers, each row shows which track(s) a customer purchased and the album that track belongs to.

# What the Query Does
* Starts at Customer to identify the buyer.
* Joins through Invoice and InvoiceLine to reach individual Track purchases.
* Joins Album to show each track’s album title.
* Sorts by LastName, FirstName for a human-readable list.

