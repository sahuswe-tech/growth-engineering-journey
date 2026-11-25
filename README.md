# growth-engineering-journey
My path from Growth Marketer to Growth Engineer
My goal is to be able to build a growth product 25 Nov 26
week1/sql-notes.md
SELECT Title, Rating FROM movies
INNER JOIN Boxoffice
ON movies.id = Boxoffice.Movie_id
ORDER BY Rating DESC;
