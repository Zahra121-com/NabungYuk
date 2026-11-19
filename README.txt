NabungYuk (versi sederhana)

Jalankan:
  pip install customtkinter
  python main.py

Tes:  python -m unittest -v

File:
  main.py          tampilan
  logika.py        baca/tulis data.txt + hitungan
  test_logika.py   unit test
  data.txt         penyimpanan data (data_contoh.txt = contoh isi)

Format data.txt:
  TARGET|id|nama|nominal|tenggat
  SETOR|id_target|tanggal|nominal|catatan
Tenggat boleh 2027-03-01 atau 2027/03/01.
