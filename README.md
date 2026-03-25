# 🍃 MongoDB Knowledge Base: The Document Store Specialist

> **"Data as Objects: Flexible, Hierarchical, and Scalable by Design."**

Repositori ini adalah **Blueprint Utama (Rak 04)** dalam ekosistem *The Learning Matrix*. Fokus utamanya adalah mengeksplorasi penyimpanan data NoSQL berbasis dokumen menggunakan MongoDB, BSON format, dan Aggregation Pipeline.

---

## 🎯 Visi Arsitektural: Schema-less Flexibility (The Why)
MongoDB menantang kekakuan tabel relasional dengan menawarkan model data polimorfik:
1.  **Document Model**: Menyimpan data sebagai objek BSON (Binary JSON) yang bisa bersarang (nested).
2.  **Dynamic Schema**: Memungkinkan evolusi data tanpa migrasi skema yang menyakitkan di fase awal.
3.  **Horizontal Scalability**: Dirancang untuk tumbuh melalui *Sharding* sejak awal.

Visi repositori ini adalah membedah **MongoDB as a Primary Data Store**:
1. **Developer-Centric**: Bagaimana data disimpan mirip dengan struktur objek di bahasa pemrograman.
2. **High Performance**: Optimasi *Embedded Documents* untuk mengurangi *Round-trip* I/O.
3. **Complex Analytics**: Pemanfaatan *Aggregation Pipeline* untuk pemrosesan data real-time.

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: JavaScript/Python/Go (Logic Core).
- **Sumbu-X**: RAK-02 (Server Runtime) ➡️ **RAK-04 (Storage Hub)**.

Di sini kita belajar **"Bagaimana menyimpan objek kompleks tanpa harus memecahnya ke belasan tabel JOIN"**.

---

## 🏗️ Struktur 8-Rak (The Taxonomy)
1. **RAK-01: Anatomy & Landscape** (Sejarah NoSQL, Document vs Relational, BSON Spec).
2. **RAK-02: Foundation & Core Rules** (CRUD Operations, Query Operators, Data Types).
3. **RAK-03: Evolution & Interfacing** (Indexing Strategies, Geospatial Query, GridFS).
4. **RAK-04: Core Mechanics & Internals** (WiredTiger Engine, Journaling, Caching Layer).
5. **RAK-05: Ecosystem & Tooling** (Mongosh, MongoDB Compass, Atlas CLI).
6. **RAK-06: The Underworld** (Replica Sets, Sharding Mechanics, Election Process).
7. **RAK-07: Specialization** (Aggregation Pipeline Mastery, Change Streams, Security).
8. **RAK-08: Matrix Intersection** (The Bridge: How MongoDB scales with RAK-06 Infrastructure).

---

## 📊 Status Proyek
Detail status per Rak dapat dilihat di [status.md](./status.md).

> [!NOTE]
> Proyek ini mengikuti standar dokumentasi **Gold Standard PPM V4**.

- `README.md` adalah pendahuluan ini.
- `docs/` berisi dokumentasi pendukung (pemetaan, aturan, referensi).
- `RAK-xx/` berisi semua rak utama.

## Dokumentasi
- [docs/root-governance.md](./docs/root-governance.md)