# pdf-miner
python based crawler to mine pdfs from websites related to research works and extract useful features like author name, emails.

## Requirements:

For python3

1. pypdf2
2. pymysql
3. nltk (tokenizer)
4. pyenchant (otherwise known as  pyenchant)
5. BeautifulSoup
6. urllib
7. requests 
8. pdftohtml

## Database Settings:

Make a database on localhost named "authors_db".
In "authors_db" create a table named "nameemail" having the following fields:

email              varchar    length: 500 (make it unique to avoid duplication)
name               varchar    length: 500
info               varchar    length: 500
website            varchar    length: 500

```
user: root
password: admin123
```
Process:

Place domains list in finalDomain.txt
Start automate.py

```
python automate.py
```
