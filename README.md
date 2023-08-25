# WEATHER-
Query the list of CITY names from STATION that do not start with vowels. 

SELECT DISTINCT CITY
FROM STATION
WHERE CITY NOT REGEXP '^[aeiouAEIOU]';

This query retrieves distinct city names from the STATION table where the city name does not start with a vowel (either lowercase or uppercase). It uses the NOT REGEXP condition to filter out city names that start with a vowel.




