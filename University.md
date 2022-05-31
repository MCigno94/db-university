## DB University

## Tables

## DEPARTMENTS

id:
name:
description:
places_available:
access examination: TINYINT DEFAULT('YES')

## DEGREE_COURSES

id:
name:
course:
?teacher?
?exam_appeals?

## TEACHERS

id:
name:
lastname:
age:
?subjects?

## SUBJECTS

id:
name:

## EXAM_APPEALS

id:
name:
?teacher?

## EXAM

id:
credits:

## VOTES

id:
positive:
negative:
?exam_appeals?

## STUDENTS

id:
name:
lastname:
age:
email:
telephon:
addres:
?degree_courses?
