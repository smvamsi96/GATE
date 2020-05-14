Any thing that can be recorded is data.
A collection of related data is called a database.
Entity type is the object, where as an entity is an instance.
Attributes:
- Simple
- Composite(full name is composed of first, middel and last names)
- Single Valued(like age)
- Multi Valued(like phone number)
- Stored
- Derived(storing both age AND date-of-birth is redundant)
- Complex - A combination of composite & multi-valued attributes
We use NULL value in the database if the attribute is not applicable for an instance.
Relationships could be one-many(like person-phoneNumbers), many-one, m-n(like employee-projects), recursive(like employee-supervisor), identifying relationships(like employee-family).
Any Entity that have uniqueness constraint is called a Strong Entity andEntities that do not are called Weak Entity.
You can give constraints to columns in the databases.
Possible constraints: Unique, 
We can add many attributes to form a Unique Key attribute.
Because Weak Entity depends on Strong Entity for identity, every weak entity must have total participation in a relationship with strong entity.
Attributes for a relationship should avoided except in the case of many-many relationships.
If you want to assign an attribute to a relationship,
for one-many -> give it to the "one" side of the relationship
for one-one -> both sides are okay
for many-many -> give the attribute to the relationship
