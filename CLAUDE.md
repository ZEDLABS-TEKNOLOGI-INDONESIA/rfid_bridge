# rfid_bridge

**Status**: Aktif (Produksi)
**Kategori**: IoT — RFID Bridge

## Deskripsi
Bridge RFID berbasis Rust. Membaca kartu RFID dari reader USB/serial dan meneruskan data ke backend presensi. firmware/ untuk microcontroller companion.

## Tech Stack
- Rust
- Firmware: (embedded)

## Catatan
- install.sh: script instalasi di server/raspi
- Cargo.lock/Cargo.toml: Rust project
- Berbeda dengan attendance-machine (ESP32) — ini untuk reader USB yang terhubung ke PC/Raspi
