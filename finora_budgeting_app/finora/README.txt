FINORA — Budgeting Web App
============================

Versi ini adalah prototype lengkap yang bisa langsung dibuka di browser.

Fitur:
- Dashboard saldo, pemasukan, pengeluaran, savings rate
- Transaksi pemasukan/pengeluaran
- Kategori
- Budget bulanan per kategori
- Target tabungan
- Laporan & insight
- Grafik 6 bulan
- Pencarian/filter transaksi
- Export backup JSON
- Responsive desktop/mobile
- Data lokal memakai localStorage

CATATAN CLOUD / MULTI-DEVICE:
HTML standalone tidak dapat membuat akun email dan menyimpan data lintas perangkat tanpa backend/database.

Untuk versi produksi:
1. Buat project Supabase atau Firebase.
2. Aktifkan email/password authentication.
3. Buat tabel transaksi, budgets, goals, profiles.
4. Gunakan user_id/auth.uid agar data setiap email terpisah.
5. Ganti localStorage pada app.html dengan query database.
6. Deploy ke Vercel/Netlify/Cloudflare Pages.

Dengan setup tersebut, satu orang dapat login dari HP/laptop berbeda dan datanya tetap sama.
Orang lain dapat membuat akun sendiri dan hanya melihat data miliknya.

File app.html dapat langsung dibuka dengan double-click.
