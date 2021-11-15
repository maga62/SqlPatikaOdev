# SqlPatikaOdev

#odev1

1. select title,description  From filim;
2. Selcet * from from filim where  length>60 AND length<75
3. select * from filim where rental_rate=0,99 and replacment_cost=12,99 or replacment =28.99
4. select * from  custormer where first_name='Mary'
5. select *from filim WHERE NOT (length> AND rental_rate = 4.99 OR rental_rate = 2.99)

#odev2
###film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)
1  selecet * from filim where between 12,99 and 16,99
###actor tablosunda bulunan first_nameve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)
2  selecet first_nameve , last_name from  actor first_name IN('Nick','Penelope','Ed')

film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)
1 select * from filim 
2 where rental_rate IN (0.99, 2.99, 4.99) AND  replacement_cost IN (12.99, 15.99, 28.99)



1.  selecet * from filim where between 12,99 and 16,99
2.  soru
3.  selecet first_nameve , last_name from  actor first_name IN('Nick','Penelope','Ed')
3soru
5. 1 select * from filim 
6. 2 where rental_rate IN (0.99, 2.99, 4.99) AND  replacement_cost IN (12.99, 15.99, 28.99)
