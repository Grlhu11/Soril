## Системийн тайлбар
Airport database system

## Ашиглах заавар
1. MySQL server ажиллуулна
2. mysqlScript.sql файлыг нээнэ
3. Бүх кодыг run хийнэ

## Үр дүн
- Database үүснэ
- Tables үүснэ
- Data орно
- Query ажиллана

  ## Файлын бүтэц

/project
├── mysqlScript.sql
└── README.md

## Security

- admin_user → бүх эрхтэй
- report_user → зөвхөн SELECT

## Backup & Restore

Backup:
mysqldump -u root -p airport_db > backup.sql

Restore:
mysql -u root -p airport_db < backup.sql

## Оюутны мэдээлэл

Нэр: Gerelkhuu
Код: B222270118
GitHub: (https://github.com/Grlhu11/Soril/edit/main/README.md)
