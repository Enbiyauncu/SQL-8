# SQL-8
SQL ÖDEV 8 TABLO OLUŞTURMA

--1-- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE table employee (
id INTEGER,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)	
);

--2--Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
insert into employee (id, name, birthday, email) values (1, 'Sibby', '2022-09-21', 'swodham0@mlb.com');
insert into employee (id, name, birthday, email) values (2, 'Nanci', '2022-06-21', 'nrollins1@nhs.uk');
insert into employee (id, name, birthday, email) values (3, 'Xever', '2023-04-28', 'xgreville2@disqus.com');
insert into employee (id, name, birthday, email) values (4, 'Kare', '2022-07-03', 'kshutte3@usnews.com');
insert into employee (id, name, birthday, email) values (5, 'Vivi', '2022-07-17', 'vantonoyev4@behance.net');
insert into employee (id, name, birthday, email) values (6, 'Olwen', '2022-06-26', 'oesslemont5@cnbc.com');
insert into employee (id, name, birthday, email) values (7, 'Wenonah', '2022-09-07', 'wdurgan6@ow.ly');
insert into employee (id, name, birthday, email) values (8, 'Silvano', '2023-04-10', 'sstickney7@php.net');
insert into employee (id, name, birthday, email) values (9, 'Mommy', '2022-07-03', 'mitzhak8@shinystat.com');
insert into employee (id, name, birthday, email) values (10, 'Pauletta', '2022-11-22', 'pgunstone9@yolasite.com');
insert into employee (id, name, birthday, email) values (11, 'Cobb', '2022-12-11', 'cwarnocka@digg.com');
insert into employee (id, name, birthday, email) values (12, 'Emmye', '2023-03-24', 'earchbaldb@cdc.gov');
insert into employee (id, name, birthday, email) values (13, 'Efrem', '2022-07-23', 'eosbaldstonec@kickstarter.com');
insert into employee (id, name, birthday, email) values (14, 'Diarmid', '2023-03-17', 'dklimtd@cafepress.com');
insert into employee (id, name, birthday, email) values (15, 'Kacey', '2023-03-01', 'kmaddisone@hugedomains.com');
insert into employee (id, name, birthday, email) values (16, 'Martelle', '2022-11-17', 'mcasettif@ucla.edu');
insert into employee (id, name, birthday, email) values (17, 'Edna', '2022-10-31', 'etootellg@ebay.co.uk');
insert into employee (id, name, birthday, email) values (18, 'Powell', '2023-04-07', 'pwrightimh@spiegel.de');
insert into employee (id, name, birthday, email) values (19, 'Anissa', '2022-06-07', 'apailini@sphinn.com');
insert into employee (id, name, birthday, email) values (20, 'Ebba', '2022-11-17', 'eruddlej@opensource.org');
insert into employee (id, name, birthday, email) values (21, 'Cissy', '2023-01-07', 'caltik@bandcamp.com');
insert into employee (id, name, birthday, email) values (22, 'Jonah', '2023-01-13', 'jwoolnoughl@google.es');
insert into employee (id, name, birthday, email) values (23, 'Pippy', '2023-02-11', 'pbifieldm@about.com');
insert into employee (id, name, birthday, email) values (24, 'Barbee', '2022-06-09', 'bbuntn@mlb.com');
insert into employee (id, name, birthday, email) values (25, 'Russell', '2022-06-01', 'rboxhallo@gov.uk');
insert into employee (id, name, birthday, email) values (26, 'Waring', '2023-04-13', 'wbardeyp@chron.com');
insert into employee (id, name, birthday, email) values (27, 'Irvine', '2023-02-14', 'ijeffersonq@4shared.com');
insert into employee (id, name, birthday, email) values (28, 'Kimberlee', '2023-01-15', 'kstruthersr@cdbaby.com');
insert into employee (id, name, birthday, email) values (29, 'Aile', '2023-03-26', 'ahatzars@stumbleupon.com');
insert into employee (id, name, birthday, email) values (30, 'Kippar', '2023-02-13', 'kghidottit@ted.com');
insert into employee (id, name, birthday, email) values (31, 'Winona', '2023-01-11', 'wbyersu@pbs.org');
insert into employee (id, name, birthday, email) values (32, 'Isadore', '2022-12-24', 'isutherelv@liveinternet.ru');
insert into employee (id, name, birthday, email) values (33, 'Julius', '2023-01-30', 'jwanklynw@csmonitor.com');
insert into employee (id, name, birthday, email) values (34, 'Fulton', '2022-08-31', 'fmacgrayx@wikispaces.com');
insert into employee (id, name, birthday, email) values (35, 'Vinnie', '2023-05-26', 'vkaasmanny@unesco.org');
insert into employee (id, name, birthday, email) values (36, 'Jordana', '2022-07-30', 'jkeemerz@amazon.de');
insert into employee (id, name, birthday, email) values (37, 'Peyter', '2023-03-01', 'pflescher10@altervista.org');
insert into employee (id, name, birthday, email) values (38, 'Branden', '2023-03-03', 'borrah11@nps.gov');
insert into employee (id, name, birthday, email) values (39, 'Luci', '2022-08-12', 'lpiletic12@youtu.be');
insert into employee (id, name, birthday, email) values (40, 'Kathrine', '2022-11-30', 'kdell13@digg.com');
insert into employee (id, name, birthday, email) values (41, 'Harriott', '2022-07-29', 'hdurnford14@de.vu');
insert into employee (id, name, birthday, email) values (42, 'Janine', '2022-12-04', 'jsacchetti15@wiley.com');
insert into employee (id, name, birthday, email) values (43, 'Georgianna', '2022-07-06', 'gbuten16@rambler.ru');
insert into employee (id, name, birthday, email) values (44, 'Alessandra', '2022-06-11', 'areubbens17@weather.com');
insert into employee (id, name, birthday, email) values (45, 'Peta', '2022-10-26', 'pjaray18@google.co.jp');
insert into employee (id, name, birthday, email) values (46, 'Von', '2022-12-13', 'vblacker19@nymag.com');
insert into employee (id, name, birthday, email) values (47, 'Jackqueline', '2023-01-21', 'jbarstock1a@arstechnica.com');
insert into employee (id, name, birthday, email) values (48, 'Dorothea', '2022-07-13', 'dnegal1b@technorati.com');
insert into employee (id, name, birthday, email) values (49, 'Pavia', '2023-02-10', 'phegley1c@yelp.com');
insert into employee (id, name, birthday, email) values (50, 'Rakel', '2023-05-15', 'rnortham1d@eventbrite.com');

--3--Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee
SET name = 'Enbiya'
WHERE id = 1

UPDATE employee
SET birthday = '2016-07-11'
WHERE name = 'Olwen'

UPDATE employee
SET email = 'patika@sql.com'
WHERE birthday = '2023-04-10'

UPDATE employee
SET name = 'Buse'
WHERE email = 'wdurgan6Qow.ly'

UPDATE employee
SET birthday = '1998-07-11'
WHERE id = 9

--4--Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee
WHERE name ='Nanci';

DELETE FROM employee
WHERE birthday = '2022-09-07';

DELETE FROM employee
WHERE id = 21;

DELETE FROM employee
WHERE name LIKE 'Pa%';

DELETE FROM employee
WHERE email = 'wbyersu@pbs.org';
