# Best Practices in Databases

Databases are essentially a collection of tidy datasets with relationships between the tables specified. Generally, but not exclusively, databases in the Region are developed using MSAccess.

- Variable names in each table should be described (i.e., a data dictionary is available for each table). When possible, the database should be documented within the database application (e.g. from within MS Access, add title and abstract to database properties and add description for all tables and fields)
- Enforce constraints on variables to promote Quality Assurance (see [Quality Management](../../../fundamental-activities/quality-management.md) section). For example, in a variable named “Gender,” inputs could be constrained to the values of “Female,” “Male,” and “Unknown;"  in a variable named “Length\_mm,” only integers between 10 and 1000 may be allowable values.
- If possible, consider converting MSAccess databases to SQLite, an open format that will preserve the database functionality. Utilities are available to assist with this, but may require additional technical assistance. Contact your DST member if you are interested in this conversion.
- If conversion is not possible, MSAccess tables and their data dictionaries should be exported to a preferred open format (e.g. Text or CSV) and the database structure (relationships diagram in MSAccess) should be saved to a preferred open format (e.g. JPEG or PNG) throughout the duration of the project and at the completion of the project. These files are stored in the same archive folder as the database.
