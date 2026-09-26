# Catatan Ide — Layanan Surat Online

Ide untuk fase berikutnya. **Belum dikerjakan.**

## Fase 3 — JS + data dummy
- Tombol buka/tutup sidebar di layar sempit (sekarang nav langsung horizontal).
- Pilih jenis surat → tampilkan hanya fieldset detail yang relevan (progressive disclosure),
  bukan keempatnya sekaligus seperti sekarang.
- Validasi form bertahap per langkah; tampilkan pesan galat di dekat field.
- Pratinjau nama berkas yang dipilih sebelum dikirim.

## Fase 4 — Backend (Supabase) + DB
- Auth warga (email + kata sandi), tabel pengajuan, tabel berkas, Supabase Storage.
- Row Level Security: warga hanya melihat pengajuan miliknya.
- Ganti data dummy di dashboard/lacak dengan data nyata.

## Fase 5 — Alur status + PDF
- Petugas mengubah status (Diajukan → Diverifikasi → Disetujui/Ditolak → Selesai).
- Riwayat status otomatis bertambah dari perubahan status.
- Generate PDF surat + tombol unduh aktif hanya saat status Selesai.

## Fase 6 — Polish + deploy
- Halaman petugas/admin (ditunda sejak Fase 1).
- Cek Lighthouse, meta deskripsi/OG, deploy statis.

## Perbaikan kecil
- Aksi "Unduh" di dashboard sebaiknya nonaktif sampai status Selesai.
- Tambah `aria-current="page"` pada tautan nav aktif.
