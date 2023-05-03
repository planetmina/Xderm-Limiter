# Xderm-Limiter
Berfungsi untuk melimit kecepatan di openWRT. intalasi berhasil untuk versi 21.X.X.X untuk versi 22 dan seterusnya belum dicoba.

Tambahkan perintah ini di startup, agar ketika restart Xderm Limiter langsung jalan:
echo Start > /www/xderm/limitdir/st;curl -s http://localhost/xderm/limit.php -d 'button1=Start' >/dev/null 2>&1
