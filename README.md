# Tugas-perpustakaan-pertemuan2
pertemuan2
void main() {
  String nama = "Ande Saputra";
  int jumlahBuku = 2;
  bool bukuSedangDipinjam = false;

  if (bukuSedangDipinjam) {
    print("Buku sedang dipinjam");
    print("Tidak dapat meminjam buku lagi");
  } else if (jumlahBuku >= 3) {
    print("Nama: $nama");
    print("Peminjaman ditolak");
    print("Maksimal peminjaman adalah 3 buku");
  } else {
    int denda = 0;
    int lamaPinjam = 7;

    if (lamaPinjam > 7) {
      denda = (lamaPinjam - 7) * 1000;
    }

    print("PERPUSTAKAAN");
    print("Nama: $nama");
    print("Jumlah buku dipinjam: $jumlahBuku");
    print("Lama peminjaman: $lamaPinjam hari");

    if (denda > 0) {
      print("Denda keterlambatan: Rp$denda");
    } else {
      print("Denda: Rp0");
    }

    print("Peminjaman berhasil");
  }
}
