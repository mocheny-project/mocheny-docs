## 🎨 BRANDING.md (Rev 2: Brand Identity & Usage Guidelines)

Dokumen ini mendefinisikan standar resmi, terminologi, dan aturan penggunaan untuk merek Mocheny Project. Dokumen ini bertujuan untuk menjaga integritas dan otoritas merek (Brand Authority) di seluruh ekosistem.

---

## ⚠️ PEMBERITAHUAN HAK CIPTA (COPYRIGHT NOTICE)

Meskipun sebagian besar dokumentasi naratif Mocheny Project dilisensikan di bawah CC BY 4.0, file **BRANDING.md** ini dan **OWNERSHIP.md** sepenuhnya tunduk pada **Copyright Pemilik** dan **BUKAN** dilisensikan di bawah CC BY 4.0 atau Apache 2.0. Kedua file ini tidak boleh dimodifikasi atau didistribusikan ulang, kecuali untuk tujuan referensi.

### 1. Naming & Capitalization (Merek Induk)

1.1. **Nama Resmi:** Merek utama kami adalah **Mocheny**.
1.2. **Penggunaan Resmi:** Gunakan "Mocheny Project" saat merujuk pada organisasi yang mengelola aset *open source*.
1.3. **Aturan Kapitalisasi:**
    * Selalu gunakan **Mocheny** dengan **'M' kapital** dan sisa huruf kecil.
    * TIDAK PERNAH menulis: MOCHENY, Mocheny!, Mocheny-Project.

### 2. Produk Inti (Branded House)

Semua produk inti menggunakan formula **Mocheny + [Descriptor]** dan harus dikapitalisasi sebagai berikut:

| Nama Produk | Deskripsi Fungsi | Repo Terkait |
| :--- | :--- | :--- |
| **Mocheny CLI** | Mesin *core* dan *command-line tool*. | `mocheny-project/mocheny-cli` |
| **Mocheny Envabox** | Koleksi *ready-made development environment* (Docker) dan *easy deploy* ke Jelastic. | `mocheny-project/mocheny-envabox` |
| **Mocheny Edna** | *Edge Native CMS Core* yang terinspirasi dari WordPress Ecosystem. | `mocheny-project/mocheny-edna` |

### 3. Nomenklatur Teknis (Glossary Wajib)

Istilah berikut adalah **Brand Terminology** resmi Mocheny dan harus digunakan secara konsisten dalam semua dokumentasi dan komunikasi teknis:

| Elemen Terminologi | Definisi Mocheny (Harus Konsisten) | Jangan Gunakan |
| :--- | :--- | :--- |
| **Pipeline** | *Deployment flow* yang didefinisikan secara deklaratif (CI/CD). | *Workflow*, *Job Queue*. |
| **State** | Konfigurasi lingkungan yang disimpan dan dapat diulangi. | *Setting*, *Preset*. |
| **Parity** | Konsistensi *State* antar lingkungan (Staging vs. Production). | *Sync*, *Match*. |
| **Observer** | Sistem pengumpulan metrik dan *logging* non-blocking. | *Telemetry*, *Tracking*. |
| **Artifact** | *Output* terkompilasi yang di-*cache* dan disimpan dalam *registry*. | *Binary*, *Build*. |

### 4. Aturan Penggunaan Merek (Trademark Defense)

Aturan ini berlaku untuk semua pihak eksternal, komunitas, dan kontributor:

4.1. **Penggunaan Nama Produk:** Pihak eksternal TIDAK DIPERBOLEHKAN menggunakan nama produk resmi Mocheny (e.g., Mocheny Envabox, Mocheny Edna) untuk **distribusi *fork*** atau produk *open source* turunan mereka.

4.2. **Klaim Kemitraan:** Anda tidak boleh menyiratkan kemitraan, dukungan, atau afiliasi resmi dengan Mocheny Project tanpa izin tertulis dari Pemilik.

4.3. **Integrasi:** Jika Anda membuat *plugin* atau *module* yang terintegrasi dengan Mocheny, beri nama produk Anda dengan jelas (e.g., *AcmeCorp's Plugin for Mocheny CLI*), bukan *Mocheny Acme Plugin*.

4.4. **Penggunaan Logo:** (Akan disempurnakan setelah logo tersedia). Penggunaan logo hanya diizinkan untuk tujuan merujuk Mocheny Project secara resmi.

### 5. Standard Teknis (Kode & URL)

5.1. **Casing Kode:**
    * **Repo/URL/Package Manager:** Gunakan *kebab-case* (`mocheny-cli`).
    * **Library/SDK:** Gunakan *PascalCase* (`MochenyAuthSDK`).
    * **Variable/Fungsi:** Gunakan *snake_case* atau *camelCase* sesuai bahasa pemrogramannya.

5.2. **Struktur Repository:** Setiap repository produk inti (`mocheny-cli`, `mocheny-envabox`, `mocheny-edna`) akan diatur sebagai **pnpm Monorepo** internal untuk memfasilitasi pengembangan *packages* yang modular dan efisien.

5.3. **Official Registry:** Pengguna harus selalu diarahkan ke **`ghcr.io/mocheny-project`** untuk *artifact* resmi yang terpercaya.

---
