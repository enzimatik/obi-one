# Cara Melakukan PCR serta Visualisasinya

#molecularbiology #pcr #indonesian

## Reaksi PCR

### Alat

- [ ] Micropipette
- [ ] Microtips 10, 100, 200 µL
- [ ] Microcentrifuge Tube 1.5 mL
- [ ] Tube rack
- [ ] Ice bucket
- [ ] Thermocycler

### Bahan

- [ ] Gloves
- [ ] Tissue
- [ ] Alcohol 70%
- [ ] Trash bag
- [ ] Tube PCR 0.2 mL 
- [ ] Nuclease Free Water (NFW)
- [ ] PCR Buffer 10x
- [ ] MgCl2 25 mM
- [ ] dNTPS each 10 mM
- [ ] Primer Forward dan Reverse 10 µM
- [ ] Taq polymerase 5 unit/µL
- [ ] Sample DNA 20 ng/µL

>**Notes**
>- PCR buffer, MgCl<sub>2</sub>, dan Taq polymerase tersedia dalam satu kit
>- Primer dapat disiapkan terpisah/masing-masing atau disatukan (_recommended_)

### Sebelum Bekerja

- Hitung kebutuhan reagen yang diperlukan
- Pastikan semua bahan dan sample mencukupi untuk eksperimen
- Gunakan sarung tangan
- Bersihkan tempat bekerja dan peralatan dengan alcohol 70%
- Sinari tempat kerja dan peralatan dengan lampu UV (opsional)
- Siapkan wadah sampah, wadah es, rak tabung
- Aliquot reagen stok (opsional)

### Setelah Bekerja

- Bersihkan tempat bekerja dan peralatan dengan alcohol 70% dan keringkan
- Sinari tempat kerja dan peralatan dengan lampu UV (opsional)
- Buang wadah sampah, es pada wadah es

### Protokol

1. [ ] Cairkan bahan dan sample. Setelah cair simpan di wadah es.
2. [ ] Buat PCR mastermix dengan mencampurkan reagen pada microcentrifuge tube 1.5 mL secara berurutan sebagaimana tabel berikut:

**Components** | **Volume 1x** (µL) | **Stock** | **Final conc.**
------------ | ------------ | ------------ | ------------ 
NFW | 1.75 | - | -
PCR Buffer | 2 | 10x | 1x
MgCl<sub>2</sub> | 2 | 25 mM | 2 mM
dNTPS mix | 0.5 | 10 mM | 250 µM
Primer FR | 0.5 | 10 µM | 250 nM
Taq polymerase | 0.1 | 5 unit/µL | 0.625 unit/ reaction

3. [ ] Pindahkan PCR mastermix ke masing-masing tabung PCR sebanyak 23 µL
4. [ ] Tambahkan sample DNA sebanyak 2 µL (konsentrasi final 20 ng/reaksi)
5. [ ] Spindown tabung PCR dan pastikan sample DNA tercampur kedalam mix
6. [ ] Buat dan kemudian jalankan protocol PCR sebagai berikut

**Step** | Time | **Temperature** | **Comment**
------------ | ------------ | ------------ | ------------ 
**Heat Activation** | 5 min | 95°C | optional, enzyme with inhibitor
	**Cycling** <br/> - Denaturation <br/> - Annealing <br/> - Elongation| <br/>10 sec <br/> 30 sec <br/> 20 sec <br/> | <br/> 95°C <br/> 55°C <br/> 72°C <br/> | 40 cycle
**Final Extension** | 2 min | 72°C |
Storage  | ∞ | 4°C | optional

7. [ ] Simpan hasil PCR pada kulkas dengan suhu 4 °C atau freezer -20 °C

>**Note**
>- Suhu annealing primer bergantung pada desain primer dan reagen yang digunakan. Pastikan primer yang digunakan telah dilakukan optimasi suhu annealing (Ta) maupun konsentrasi PCR mastermix
>- Pengambilan bahan dibawah 1 µL seringkali tidak akurat, sehingga mastermix sebaiknya dibuat untuk beberapa reaksi
>- Bekerja secara cepat dan tepat untuk mencegah kontaminasi serta mengurangi waktu paparan reagen pada suhu ruang.

## Visualisasi hasil dengan gel electrophoresis

> **Warning**
> - Gunakan senyawa pewarna lain selain EtBr bila tersedia (SYBR safe, florosafe, etc)
> - EtBr bersifat toksik karena dapat mengikat DNA dan merupakan senyawa mutagen kuat.
> - Buang sarung tangan yang digunakan untuk menyiapkan atau menyentuh bahan denga EtBr terlarut.
> - Jangan gunakan peralatan lain (buku, handphone, etc) sebelum membuang sarung tangan terkontaminasi EtBr dengan benar
> - Agarose yang telah cair memiliki suhu yang tinggi, gunakan pengaman dan pastikan wadah yang digunakan sesuai

### Sebelum memulai

- Tentukan konsentrasi agarose yang akan dibuat berdasarkan table berikut

**Matrix** | **Concentration (in TAE or TBE)** | **Run** | **Comment**
------------ | ------------ | ------------ | ------------
Agarose | 2% | 100v, 30 mins | <200 bp amplicon

- Bersihkan cetakan gel menggunakan alcohol 70%
- Tentukan metode pewarnaan yang digunakan (embed atau staining)


### Visualisasi Menggunakan Agarose

1. [ ] Timbang agarose dan masukan ke dalam labu Erlenmeyer 250 mL
2. [ ] Tambahkan buffer TAE 1x
3. [ ] Larutkan agarose menggunakan microwave atau waterbath
4. [ ] Tunggu beberapa saat hingga larutan agarose menjadi hangat
5. [ ] (**Embeded Method, abaikan step 10**) Tambahkan pewarna DNA. Goyang labu Erlenmeyer hingga pewarna larut secara merata.
6. [ ] Tuangkan laurtan agarose pada cetakan gel yang tersedia dan biarkan gel mengeras
7. [ ] Masukan gel kedalam bak berisi buffer (TAE atau TBE) dan pastikan terendam
8. [ ] Buat loading mix dengan mencampurkan bahan sebagai berikut
	- Ladder: 3 µL loading dye, 5 µL NFW, 2 µL DNA ladder,
	- Sample (PCR mix tanpa dye): 3 µL loading dye, 7 PCR sample
	- Sample (PCR mix dengan dye): lanjut ke tahap 7
9. [ ] Masukan sample ke well gel dan jalankan mesin elektroforesis
10. [ ] (**Staining Method, abaikan step 5**) rendam gel pada laurtan pewarna selama 20 menit, kemudian rendam dengan aquadest selama 5 menit
11. [ ] Angkat gel dan amati menggunakan UV box/gel documentation system

## Troubleshoot

**Problem** | **Troubleshoot**
------------ | ------------
Pita DNA tidak terlihat | Ulangi PCR
