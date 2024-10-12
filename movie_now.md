- Report summary statistics, such as the minimum, maximum, average, and count, of ratings for the movie with ID 25.

```
SELECT min(rating) as min_rating,
	   max(rating) as max_rating,
	   round(avg(rating),2) as avg_rating,
	   count(rating) number_ratings
FROM renting
where movie_id=25;
```
![alt text](image.png)

