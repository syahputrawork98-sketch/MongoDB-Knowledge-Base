# 🍃 MongoDB Knowledge Base: The Document Store Specialist

> **"Data as Objects: Flexible, Hierarchical, and Scalable by Design."**

## 📖 Apa itu MongoDB? (The What)
**MongoDB** adalah sistem basis data NoSQL berbasis dokumen (*Document Store*) paling populer di dunia. Berbeda dengan database tradisional yang menyimpan data dalam baris dan kolom yang kaku, MongoDB menyimpan data dalam dokumen fleksibel mirip JSON (disebut BSON).

Dalam ekosistem *The Learning Matrix*, MongoDB mewakili paradigma **Polymorphism & Horizontal Scaling**: di mana data bisa memiliki bentuk yang berbeda-beda dalam satu koleksi yang sama, dan sistem bisa tumbuh besar dengan cara membagi beban ke banyak server (*Sharding*).

---

## 🎯 Mengapa Kita Menggunakan MongoDB? (The Why)
MongoDB menantang kekakuan tabel relasional dengan menawarkan keunggulan strategis:
1.  **Iterasi Cepat (Agility)**: Kamu tidak perlu menunggu migrasi skema yang rumit hanya untuk menambah satu *field* baru. Sangat cocok untuk *MVP* dan *Rapid Development*.
2.  **Mapping Alami ke Kode**: Objek di JavaScript/TypeScript/Python bisa langsung disimpan ke MongoDB tanpa perlu banyak transformasi (Object-Document Mapping).
3.  **Data Hierarkis (JSON-like)**: Kamu bisa menyimpan data kompleks (seperti alamat di dalam user) dalam satu dokumen, alih-alih melakukan `JOIN` antar tabel yang lambat.
4.  **Skalabilitas Masif**: Dirancang untuk menangani beban data terabyte hingga petabyte secara otomatis melalui mekanisme *Cluster*.

---

## 🧭 Visi Arsitektural: MongoDB as a Primary Data Store
Repositori ini membedah MongoDB melalui tiga lensa utama:
1. **Developer-Centric**: Bagaimana data disimpan mirip dengan struktur objek di bahasa pemrograman.
2. **High Performance**: Optimasi *Embedded Documents* untuk mengurangi *round-trip* I/O ke disk.
3. **Complex Analytics**: Pemanfaatan *Aggregation Pipeline* untuk pemrosesan data real-time yang canggih.

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: JavaScript/Python/Go (Logic Core).
- **Sumbu-X**: RAK-02 (Server Runtime) ➡️ **RAK-04 (Storage Hub)**.

Di sini kita belajar **"Bagaimana menyimpan data kompleks tanpa harus memecahnya menjadi belasan tabel yang saling mengunci"**.

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