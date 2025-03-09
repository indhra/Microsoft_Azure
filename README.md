# Microsoft_Azure
 Microsoft Azure cloud topics, data factory, ADLS


# Data types
1. Strucutred Data
   1. Tabular data; with fixed schema; i.e template is fixed, and data is stored in rows and columns
2. Semi - structure data
   1. Similar to a tabulard data it has some structure in it but not fully structured
   2. like a JSON file, 
   3. like while collecting data, some users may have some extra fields, some may not, like extra mail ID
3. Unstructured data
   1. Videa, audio, images, text files, etc
   2. there is no proper structure in which this data is represented


# Data Stores
Two broad categories of data store 
1. File stores
   1. Specific file format used to store data depends on a number of factors
   2. common file formats
      1. Delimited text files; csv
      2. JSON; JavaScript Object Notation
      3. Binary Large Object ; BLOB
         1. ultimately, all files are stored as binary data 1's and 0's
         2. however like above we need data to be human interpretable
         3. common types of dat stored as binary include images, video , audio 
      4. Optimized file formats
         1. above file formats are user friendly but not optimized for storage
         2. we need specialized formats for storing data in a way that it is optimized for storage
         3. like; parquet, avro, orc
2. Databases
