# Sql statements used to extract data

1. All adoptions 
```
SELECT * FROM adoption
WHERE MovementType = 1 
```
resulting file: OAR_adoptions.csv

2. All animals who have been adopted
```
Select * from animal
inner join adoption on animal.id = adoption.AnimalId
where adoption.MovementType = 1
```
resulting file: OAR_animals.csv

3. All adopters
```
select * from owner
inner join adoption
on  owner.ID = adoption.OwnerId
```
resulting files: adopters.csv

4. Coat types
```
select * from lkcoattype
```
resulting file: coat_type.csv

5.  Coat colors
```
select * from basecolour
```
resulting file: coat_color.csv

6. Shelter Locations
```
select * from internallocation
```
resulting file: shelter_location.csv

7. Sex
```
select * from lksex
```
resulting file: animal_sex.csv




