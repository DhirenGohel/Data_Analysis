## 1.Write an SQL query using CONCAT to combine first_name and last_name columns from a users table into a single full_name column and display the result.
'''
  **Syntax**

   ' SELECT CONCAT(first_name, ' ', last_name) AS full_name FROM users; '

'''
![alt text](image.png)


## 2.Given a table called playlists with a column song_title, write a query to display all song titles in uppercase using the UPPER function.
'''
  **Syntax**

   ' SELECT UPPER(song_title) AS uppercase_song_title FROM playlists; '

'''
![alt text](image-1.png)


## 3.You have a table food_items with a column item_code that sometimes contains extra spaces at the beginning or end. Write an SQL query to select item_code values after removing all leading and trailing spaces using TRIM.
'''
  **Syntax**

   ' SELECT TRIM(item_code) AS clean_item_code FROM food_items; '

'''
![alt text](image-2.png)


## 4.In a table called movies, the column imdb_id contains codes like 'tt1234567'. Write a query to extract just the numeric part (the last 7 characters) using RIGHT and display it as movie_number.<br><br><em><strong>Hint:</strong> Use RIGHT(imdb_id, 7) to get the numeric part.</em>
'''
  **Syntax**

   ' SELECT RIGHT(imdb_id, 7) AS movie_number FROM movies; '

'''
![alt text](image-3.png)


## 5.A products table has a column sku_code where some entries use dashes (e.g. 'MOB-123-XY'). Write an SQL query to replace all dashes '-' with underscores '_' in sku_code using the REPLACE function and display the updated codes.
'''
  **Syntax**

   ' SELECT REPLACE(sku_code, '-', '_') AS updated_sku_code FROM products; '

'''
![alt text](image-4.png)





