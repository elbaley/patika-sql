1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```sql
CREATE TABLE employee (
id INTEGER PRIMARY KEY,
name VARCHAR(50) NOT NULL,
email VARCHAR(100),
birthday DATE
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```sql
insert into employee (id, name, email, birthday) values (1, 'Anstice', 'agrimditch0@printfriendly.com', '1960-08-10');
insert into employee (id, name, email, birthday) values (2, 'Cesare', 'cpacher1@europa.eu', '1989-12-22');
insert into employee (id, name, email, birthday) values (3, 'Virginia', 'vgronav2@biglobe.ne.jp', '1947-08-08');
insert into employee (id, name, email, birthday) values (4, 'Aleda', 'amessier3@geocities.com', null);
insert into employee (id, name, email, birthday) values (5, 'Pacorro', 'pchancellor4@salon.com', null);
insert into employee (id, name, email, birthday) values (6, 'Nissy', 'nfrowing5@arizona.edu', '1941-07-17');
insert into employee (id, name, email, birthday) values (7, 'Sherwynd', 'stschierse6@printfriendly.com', '1959-02-23');
insert into employee (id, name, email, birthday) values (8, 'Matthew', 'mkeasley7@amazon.co.uk', '1945-11-20');
insert into employee (id, name, email, birthday) values (9, 'Michaeline', 'mkliement8@berkeley.edu', '1957-03-08');
insert into employee (id, name, email, birthday) values (10, 'Normand', 'ndutnall9@feedburner.com', '1961-07-19');
insert into employee (id, name, email, birthday) values (11, 'Cicely', 'coraea@nationalgeographic.com', null);
insert into employee (id, name, email, birthday) values (12, 'Vale', 'vmcpikeb@dmoz.org', '1944-09-16');
insert into employee (id, name, email, birthday) values (13, 'Maurizia', 'mherchec@theatlantic.com', '1981-04-30');
insert into employee (id, name, email, birthday) values (14, 'Dolorita', 'daggliod@bigcartel.com', '1993-04-20');
insert into employee (id, name, email, birthday) values (15, 'Tedda', 'temmanuelie@cbslocal.com', '1965-12-02');
insert into employee (id, name, email, birthday) values (16, 'Rosy', 'rriellyf@psu.edu', '1965-10-03');
insert into employee (id, name, email, birthday) values (17, 'Feodora', 'fmerfing@wsj.com', '1979-12-02');
insert into employee (id, name, email, birthday) values (18, 'Meredeth', 'mshemilth@mlb.com', null);
insert into employee (id, name, email, birthday) values (19, 'Melisa', 'mrowstoni@cnn.com', '1954-11-29');
insert into employee (id, name, email, birthday) values (20, 'Lelia', 'ldumperj@harvard.edu', '1984-10-13');
insert into employee (id, name, email, birthday) values (21, 'Deidre', 'dgoraccik@altervista.org', '1951-04-06');
insert into employee (id, name, email, birthday) values (22, 'Kaela', 'kperonel@tuttocitta.it', '1986-07-16');
insert into employee (id, name, email, birthday) values (23, 'Kassey', 'kackwoodm@accuweather.com', '1956-04-02');
insert into employee (id, name, email, birthday) values (24, 'Rosina', 'rmccaben@independent.co.uk', '1949-08-31');
insert into employee (id, name, email, birthday) values (25, 'Carrie', 'cburgano@huffingtonpost.com', '1983-11-15');
insert into employee (id, name, email, birthday) values (26, 'Alisun', 'agilloolyp@irs.gov', null);
insert into employee (id, name, email, birthday) values (27, 'Garey', 'gleasonq@biblegateway.com', '1960-08-03');
insert into employee (id, name, email, birthday) values (28, 'Keenan', 'kloobyr@census.gov', null);
insert into employee (id, name, email, birthday) values (29, 'Tresa', 'tquarmbys@usnews.com', '1969-09-01');
insert into employee (id, name, email, birthday) values (30, 'Eadie', 'etuftt@umich.edu', '1950-08-02');
insert into employee (id, name, email, birthday) values (31, 'Caryl', 'cbarnwillu@cnn.com', '1958-08-11');
insert into employee (id, name, email, birthday) values (32, 'Kellie', 'kmoremanv@reuters.com', null);
insert into employee (id, name, email, birthday) values (33, 'Carlye', 'cloftingw@youtu.be', '1985-04-25');
insert into employee (id, name, email, birthday) values (34, 'Godfrey', 'gstrobanx@time.com', '1995-03-12');
insert into employee (id, name, email, birthday) values (35, 'Shandeigh', 'sthayy@jiathis.com', '1973-04-30');
insert into employee (id, name, email, birthday) values (36, 'Belia', 'bdoolez@walmart.com', '1948-10-04');
insert into employee (id, name, email, birthday) values (37, 'Elsy', 'erubinowitsch10@ucla.edu', '1952-10-15');
insert into employee (id, name, email, birthday) values (38, 'Hally', 'hmongeot11@tripadvisor.com', '1982-11-14');
insert into employee (id, name, email, birthday) values (39, 'Tawnya', 'tspittall12@zimbio.com', '1960-05-04');
insert into employee (id, name, email, birthday) values (40, 'Ashlen', 'amurden13@github.io', '1981-11-30');
insert into employee (id, name, email, birthday) values (41, 'Kermy', 'kshawcroft14@altervista.org', null);
insert into employee (id, name, email, birthday) values (42, 'Ashlin', 'aaymes15@infoseek.co.jp', '1967-03-01');
insert into employee (id, name, email, birthday) values (43, 'Eadmund', 'egantzman16@arizona.edu', '1954-03-16');
insert into employee (id, name, email, birthday) values (44, 'Devinne', 'dmedler17@unesco.org', '1954-02-23');
insert into employee (id, name, email, birthday) values (45, 'Bliss', 'bsherebrook18@google.pl', null);
insert into employee (id, name, email, birthday) values (46, 'Shelbi', 'slydiard19@yale.edu', '1960-06-18');
insert into employee (id, name, email, birthday) values (47, 'Rawley', 'rmcrobert1a@themeforest.net', null);
insert into employee (id, name, email, birthday) values (48, 'Micah', 'mtimbs1b@fema.gov', '1963-03-05');
insert into employee (id, name, email, birthday) values (49, 'Waverley', 'wcoonan1c@bing.com', '1946-02-24');
insert into employee (id, name, email, birthday) values (50, 'Reginauld', 'rmcterlagh1d@xing.com', '1965-09-22');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```sql
UPDATE employee
SET name = 'Updated!',
email='updated@update.com'
WHERE id BETWEEN 1 AND 5
RETURNING *;
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```sql
DELETE FROM employee
WHERE id BETWEEN 1 AND 5
RETURNING *;
```
