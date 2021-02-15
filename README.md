# Notes & scripts DATABASE module-UF2
SQL Workplace

## OR, AND e IN
Examples:

```sql
SELECT characters.id_character,characters.name
FROM `characters`
WHERE
	characters.id_character IN (1,3)
ORDER BY id_character DESC;


SELECT characters.id_character,characters.name
FROM `characters`
WHERE
	characters.id_character=1 OR characters.id_character=3
ORDER BY id_character DESC;

SELECT characters.id_character,characters.name
FROM `characters`
WHERE
	characters.id_character=1 AND characters.id_character=3
ORDER BY id_character DESC
