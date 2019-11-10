# NumberToTurkishLira - PHP

### Sayıyı Türk Lirası Olarak Yazıya Çevirme - PHP

**2012 yılında ASP ile hazırladığım sayıyı Türk Lirası olarak yazıya çevirme fonksiyonunu PHP'ye çevirip paylaşmak istedim.**


```php
echo NumberToTurkishLira( -0.50 );
Output: Eksi Elli Kuruş
```

```php
echo NumberToTurkishLira( -13.11 );
Output: Eksi On Üç Lira, On Bir Kuruş
```

```php
echo NumberToTurkishLira( 9.90 );
Output: Dokuz Lira, Doksan Kuruş
```

```php
echo NumberToTurkishLira( 12.12 );

Output: On İki Lira, On İki Kuruş
```

```php
echo NumberToTurkishLira( 500 );

Output: Beş Yüz Lira
```

```php
echo NumberToTurkishLira( 1000 );

Output: Bin Lira
```

```php
echo NumberToTurkishLira( 1453 );

Output: Bin Dört Yüz Elli Üç Lira
```

```php
echo NumberToTurkishLira( 1923 );

Output: Bin Dokuz Yüz Yirmi Üç Lira
```

```php
echo NumberToTurkishLira( 59421.45 );

Output: Elli Dokuz Bin Dört Yüz Yirmi Bir Lira, Kırk Beş Kuruş
```

```php
echo NumberToTurkishLira( 9458761 );

Output: Dokuz Milyon Dört Yüz Elli Sekiz Bin Yedi Yüz Altmış Bir Lira
```

```php
echo NumberToTurkishLira( 7343457483664.82 );

Output: Yedi Trilyon Üç Yüz Kırk Üç Milyar Dört Yüz Elli Yedi Milyon Dört Yüz Seksen Üç Bin Altı Yüz Altmış Dört Lira, Seksen İki Kuruş
```

```php
echo NumberToTurkishLira( 95001125453345.80 );

Output: Doksan Beş Trilyon Bir Milyar Yüz Yirmi Beş Milyon Dört Yüz Elli Üç Bin Üç Yüz Kırk Beş Lira, Seksen Kuruş
```
