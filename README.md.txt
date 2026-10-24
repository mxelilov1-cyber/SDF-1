
# Universitet Tədbirlərinin İdarə Edilməsi və Qeydiyyat Sistemi

## Layihə haqqında

Bu layihə universitetdə keçirilən tədbirlərin yaradılması, idarə edilməsi və tələbələrin həmin tədbirlərə qeydiyyatdan keçməsi üçün hazırlanmış veb tətbiqdir.

## İstifadə olunan texnologiyalar

- Python
- Flask
- SQLite
- HTML5
- CSS3
- JavaScript
- Git və GitHub

## Əsas funksiyalar

- İstifadəçi qeydiyyatı və sistemə giriş
- Tədbirlərin siyahısı
- Tədbirlərin ada, kateqoriyaya, tarixə və məkana görə axtarışı
- Tədbirlərin yaradılması, redaktəsi və silinməsi
- Tədbirlərə qeydiyyat və qeydiyyatın ləğvi
- Təkrar qeydiyyatın qarşısının alınması
- İştirakçı limitinin yoxlanılması
- Administrator paneli və statistika
- Avtomatlaşdırılmış testlər

## Quraşdırılma

Python 3 quraşdırılmış olmalıdır.

Terminalı layihənin əsas qovluğunda aç və aşağıdakı əmrləri icra et:

```bash
py -m venv .venv
```

Windows PowerShell üçün:

```powershell
.venv\Scripts\Activate.ps1
```

Kitabxanaları quraşdır:

```bash
pip install -r requirements.txt
```

Tətbiqi işə sal:

```bash
python app.py
```

Brauzerdə bu ünvanı aç:

http://127.0.0.1:5000

Verilənlər bazası ilk işə salınmada avtomatik yaradılır.

## İlkin administrator hesabı

E-poçt: admin@university.local

Şifrə: Admin123!

Bu hesab yalnız ilkin sınaq üçündür. Real istifadədən əvvəl şifrə və təhlükəsizlik parametrləri dəyişdirilməlidir.

## Testlərin işə salınması

```bash
python -m unittest discover -s tests -v
```

## Təhlükəsizlik qeydi

Layihə tədris məqsədli başlanğıc versiyadır. Real istifadədən əvvəl CSRF müdafiəsi, daha güclü konfiqurasiya, təhlükəsiz administrator hesabının yaradılması və əlavə təhlükəsizlik yoxlamaları tətbiq edilməlidir.
