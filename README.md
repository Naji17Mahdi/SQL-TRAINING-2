# SQL-TRAINING-2
21

EN: Select customers whose PostalCode is either '90210' or '10001' using IN.
DE: Wählen Sie Kunden aus, deren PostalCode entweder '90210' oder '10001' ist (verwenden Sie IN).

22

EN: Write a query to return invoices where InvoiceDate is after '2012-01-01'.
DE: Schreiben Sie eine Abfrage, die Rechnungen zurückgibt, deren InvoiceDate nach dem 01.01.2012 liegt.

23

EN: Show tracks where Name contains the substring 'love' (case-insensitive).
DE: Zeigen Sie Tracks, deren Name die Teilzeichenfolge „love“ enthält (case-insensitive).

24

EN: Select all playlists whose Name is NULL or empty.
DE: Wählen Sie alle Playlists aus, deren Name NULL oder leer ist.

25

EN: Write a query to get distinct BillingCountry values from Invoice.
DE: Schreiben Sie eine Abfrage, die die unterschiedlichen (DISTINCT) BillingCountry-Werte aus Invoice liefert.

26

EN: Find all customers whose LastName begins with 'S' and live in 'Canada'.
DE: Finden Sie alle Kunden, deren LastName mit 'S' beginnt und die in 'Canada' wohnen.

27

EN: Return tracks priced between 0.99 and 1.99 but exclude 1.49 (use a combination of conditions).
DE: Geben Sie Tracks mit Preisen zwischen 0,99 und 1,99 zurück, schließen Sie jedoch 1,49 aus (Kombination von Bedingungen).

28

EN: Show all tracks that are not of GenreId = 1 (use NOT).
DE: Zeigen Sie alle Tracks, die nicht GenreId = 1 sind (verwenden Sie NOT).

29

EN: Explain (in SQL) how you would combine conditions to get tracks that are in GenreId = 2 AND have UnitPrice < 0.99. (Write the WHERE clause.)
DE: Erklären Sie (in SQL), wie Sie Bedingungen kombinieren, um Tracks zu erhalten, die GenreId = 2 UND UnitPrice < 0,99 haben. (Schreiben Sie die WHERE-Klausel.)

30

EN: Write a query to select Track.Name, Album.Title, and Artist.Name by joining Track → Album → Artist.
DE: Schreiben Sie eine Abfrage, die Track.Name, Album.Title und Artist.Name auswählt, indem Sie Track → Album → Artist verbinden.

31

EN: Using an INNER JOIN, show Invoice.InvoiceId, Customer.FirstName, Customer.LastName for all invoices.
DE: Verwenden Sie einen INNER JOIN, um Invoice.InvoiceId, Customer.FirstName, Customer.LastName für alle Rechnungen anzuzeigen.

32

EN: Write a LEFT JOIN to display all albums and any matching artist name (show album title even if artist missing).
DE: Schreiben Sie einen LEFT JOIN, um alle Alben und ggf. den zugehörigen Künstlernamen anzuzeigen (Albumtitel auch anzeigen, wenn Künstler fehlt).


33

EN: Join InvoiceLine with Track to show InvoiceLine.InvoiceId, Track.Name, InvoiceLine.UnitPrice, and InvoiceLine.Quantity.
DE: Verbinden Sie InvoiceLine mit Track, um InvoiceLine.InvoiceId, Track.Name, InvoiceLine.UnitPrice und InvoiceLine.Quantity anzuzeigen.

34

EN: Join three tables to show Customer.FirstName, Invoice.InvoiceId, and the Invoice.Total — joining Customer → Invoice.
DE: Verbinden Sie drei Tabellen, um Customer.FirstName, Invoice.InvoiceId und Invoice.Total anzuzeigen — Verbindung Customer → Invoice.

35

EN: Use table aliases (c, i, il) to write a concise join showing customer name and invoice totals.
DE: Verwenden Sie Tabellenaliase (c, i, il), um einen kurzen Join zu schreiben, der Kundenname und Rechnungsbeträge zeigt.
