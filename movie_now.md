# PROJECT - MOVIES NOW 
## Report summary statistics, such as the minimum, maximum, average, and count, of ratings for the movie with ID 25.

```
SELECT min(rating) as min_rating,
	   max(rating) as max_rating,
	   round(avg(rating),2) as avg_rating,
	   count(rating) number_ratings
FROM renting
where movie_id=25;
```
![image](https://github.com/user-attachments/assets/1bb3791a-c888-41f7-beac-925a662f3701)

## Report total number of movie rentals, the total number of ratings and the average rating of all movies since the beginning of 2019.

```
SELECT 
	COUNT(*) AS number_renting,
	round(AVG(rating),2) AS average_rating, 
    COUNT(rating) AS number_ratings 
FROM renting
WHERE date_renting >= '2019-01-01';
```
![image](https://github.com/user-attachments/assets/941ae1d9-8fef-4e63-8dcb-5a495d570e31)






