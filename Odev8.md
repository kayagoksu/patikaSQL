1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```
create table employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE NOT NULL,
	email VARCHAR(100) NOT NULL
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```
insert into employee (name, birthday, email) values ('Monro Vannini', '1937-12-07', 'mvannini0@pen.io');
insert into employee (name, birthday, email) values ('Anya Walsh', '1985-07-30', 'awalsh1@geocities.com');
insert into employee (name, birthday, email) values ('Martita Jonuzi', '1904-08-14', 'mjonuzi2@livejournal.com');
insert into employee (name, birthday, email) values ('Barnie Piquard', '1939-08-09', 'bpiquard3@tumblr.com');
insert into employee (name, birthday, email) values ('Freemon Krier', '1945-09-14', 'fkrier4@ft.com');
insert into employee (name, birthday, email) values ('Joe Bicksteth', '1929-04-28', 'jbicksteth5@google.ca');
insert into employee (name, birthday, email) values ('Hastings Follows', '1904-01-08', 'hfollows6@twitpic.com');
insert into employee (name, birthday, email) values ('Tova Atrill', '1930-12-23', 'tatrill7@seattletimes.com');
insert into employee (name, birthday, email) values ('Vitia Chivrall', '1946-02-05', 'vchivrall8@shareasale.com');
insert into employee (name, birthday, email) values ('Farica Heymes', '1941-08-19', 'fheymes9@google.com.hk');
insert into employee (name, birthday, email) values ('Harland Fawcus', '1992-03-30', 'hfawcusa@google.es');
insert into employee (name, birthday, email) values ('Walliw Janik', '1911-12-20', 'wjanikb@oracle.com');
insert into employee (name, birthday, email) values ('Maurise O''Flaverty', '1901-12-20', 'moflavertyc@people.com.cn');
insert into employee (name, birthday, email) values ('Madelaine Colwell', '1992-11-17', 'mcolwelld@goo.gl');
insert into employee (name, birthday, email) values ('Kerwinn Izard', '1909-05-01', 'kizarde@samsung.com');
insert into employee (name, birthday, email) values ('Nico Duffet', '1918-07-21', 'nduffetf@reuters.com');
insert into employee (name, birthday, email) values ('Monika Walewicz', '1985-11-09', 'mwalewiczg@bizjournals.com');
insert into employee (name, birthday, email) values ('Margaretta Stuchberry', '1960-03-20', 'mstuchberryh@blog.com');
insert into employee (name, birthday, email) values ('Reuben Kenyon', '1915-10-25', 'rkenyoni@nbcnews.com');
insert into employee (name, birthday, email) values ('Dale Humbert', '1977-03-19', 'dhumbertj@google.es');
insert into employee (name, birthday, email) values ('Tonnie Rebillard', '1913-12-19', 'trebillardk@xinhuanet.com');
insert into employee (name, birthday, email) values ('Milicent Alten', '1918-10-02', 'maltenl@fotki.com');
insert into employee (name, birthday, email) values ('Meyer Dearsley', '1906-09-08', 'mdearsleym@google.nl');
insert into employee (name, birthday, email) values ('Gabriellia Geffcock', '1963-04-07', 'ggeffcockn@reverbnation.com');
insert into employee (name, birthday, email) values ('Nathaniel Dablin', '1908-12-04', 'ndablino@ted.com');
insert into employee (name, birthday, email) values ('Janene Goulding', '1958-09-27', 'jgouldingp@exblog.jp');
insert into employee (name, birthday, email) values ('Sukey Syer', '1968-11-08', 'ssyerq@msu.edu');
insert into employee (name, birthday, email) values ('Luce Tchaikovsky', '1973-11-09', 'ltchaikovskyr@taobao.com');
insert into employee (name, birthday, email) values ('Ransom Childerhouse', '1928-11-14', 'rchilderhouses@meetup.com');
insert into employee (name, birthday, email) values ('Rubina Dunphie', '1992-07-17', 'rdunphiet@theatlantic.com');
insert into employee (name, birthday, email) values ('Shea Prangley', '1970-03-18', 'sprangleyu@creativecommons.org');
insert into employee (name, birthday, email) values ('Gypsy Bedingfield', '1998-06-23', 'gbedingfieldv@omniture.com');
insert into employee (name, birthday, email) values ('Angelica Grovier', '1965-06-26', 'agrovierw@jimdo.com');
insert into employee (name, birthday, email) values ('Vere Pudney', '1952-05-31', 'vpudneyx@quantcast.com');
insert into employee (name, birthday, email) values ('Mara Cottee', '1961-01-01', 'mcotteey@gnu.org');
insert into employee (name, birthday, email) values ('Lancelot Bertin', '1971-07-14', 'lbertinz@smugmug.com');
insert into employee (name, birthday, email) values ('Claus Clay', '1971-06-28', 'cclay10@sphinn.com');
insert into employee (name, birthday, email) values ('Zarah Duckels', '1966-08-09', 'zduckels11@skyrock.com');
insert into employee (name, birthday, email) values ('Thebault Huerta', '1995-04-08', 'thuerta12@alexa.com');
insert into employee (name, birthday, email) values ('Kassi Rabbitts', '1943-03-03', 'krabbitts13@goo.gl');
insert into employee (name, birthday, email) values ('Grover Peeke-Vout', '1942-05-28', 'gpeekevout14@go.com');
insert into employee (name, birthday, email) values ('Edvard Fearon', '1905-09-14', 'efearon15@about.com');
insert into employee (name, birthday, email) values ('Petr Romeuf', '1968-08-19', 'promeuf16@eepurl.com');
insert into employee (name, birthday, email) values ('Currie Toderini', '1963-03-25', 'ctoderini17@mapy.cz');
insert into employee (name, birthday, email) values ('Helaina Sprague', '1945-04-01', 'hsprague18@usnews.com');
insert into employee (name, birthday, email) values ('Heather Yewdale', '1950-04-07', 'hyewdale19@wix.com');
insert into employee (name, birthday, email) values ('Rodina Corless', '1934-04-24', 'rcorless1a@msn.com');
insert into employee (name, birthday, email) values ('Stephannie Spong', '1974-12-03', 'sspong1b@unc.edu');
insert into employee (name, birthday, email) values ('Melonie Colleran', '1959-05-06', 'mcolleran1c@is.gd');
insert into employee (name, birthday, email) values ('Orly Palmby', '1923-03-23', 'opalmby1d@nasa.gov');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```
update employee
set name = 'John Doe'
where id = 3;

update employee
set birthday = '1945-02-12'
where name = 'Monro Vannini';

update employee
set email = 'free@email.com'
where id = 5;
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```
delete from employee
where id = 18;

delete from employee
where name = 'Vitia Chivrall';

delete from employee
where birthday = '1901-12-20';

delete from employee
where email = 'trebillardk@xinhuanet.com';
```
