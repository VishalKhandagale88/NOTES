- | id | name  | Country | Score |
  |----|-------|---------|-------|
  | 1  | Maria | Germany | 350   |
  | 2  | John  | USA     | 900   |
  | 3  | Georg | UK      | 750   |
  | 4  | Martin| Germany | 500   |
  | 5  | Peter | USA     | 0     |
- <pre>
  
  SELECT name, Country, Score
  FROM Players
  WHERE Score > 500
  ORDER BY Score DESC;
  </pre>
-
-