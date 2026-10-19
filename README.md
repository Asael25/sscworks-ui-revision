# SSC Works — UI/UX Revision

Repositori ini berisi implementasi dan revisi UI/UX untuk website resmi **SSC Works** (PT Surya Sarana Cipta).

## Struktur Branch Kolaborasi

Proyek ini menggunakan strategi percabangan berikut:

- **`main`**: Branch utama yang stabil (production-ready). Hanya menerima perubahan yang sudah teruji dan disetujui (via Pull Request).
- **`update`**: Branch pengembangan aktif (*staging / development*). Semua pembaruan fitur terbaru, perbaikan bug, dan kolaborasi antar developer dikerjakan di branch ini sebelum digabungkan (*merge*) ke `main`.

---

## Alur Kerja Kolaborasi (Workflow Tim)

1. **Clone Repositori:**
   ```bash
   git clone <URL_REPO_GITHUB>
   cd stitch_ssc_works_ui_ux_revision
   ```

2. **Bekerja di Branch Update:**
   ```bash
   git checkout update
   git pull origin update
   ```

3. **Membuat Feature Branch (Opsional / Dianjurkan):**
   ```bash
   git checkout -b feature/nama-fitur
   # Lakukan perubahan...
   git add .
   git commit -m "feat: penjelasan perubahan"
   git push origin feature/nama-fitur
   ```

4. **Kirim Perubahan ke Branch `update`:**
   Buat Pull Request (PR) ke branch `update` di GitHub untuk ditinjau oleh tim developer.

---

## Menjalankan Proyek

Buka file `code.html` secara langsung di browser atau gunakan ekstensi Live Server di VS Code.
