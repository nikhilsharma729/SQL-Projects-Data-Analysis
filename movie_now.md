- Report summary statistics, such as the minimum, maximum, average, and count, of ratings for the movie with ID 25.

```
SELECT min(rating) as min_rating,
	   max(rating) as max_rating,
	   round(avg(rating),2) as avg_rating,
	   count(rating) number_ratings
FROM renting
where movie_id=25;
```
![image](https://github.com/user-attachments/assets/78f48cd6-21ba-41cf-a8f8-b8731d9f142b)


