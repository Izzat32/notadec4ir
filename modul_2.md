
# Modul 2
PENTING GILA TOPIK NI

* Komponen dlm drone:
   * Flight controller (FC) (Pengendali utama)
    * IMU sensor (INU = Inertial Measurement Unit):
      * Accelerometer (Mengukur kadar pecutan/kelajuan) (Measures acceleration)
      * Gyroscope (Mengukur kadar putaran) (Measures angular rotation)
      * Magnetometer (Mengesan medan elektrik/graviti) (Basically kompas la)
      * Barometer (Megukur tekanan udara: guna utk kira altitude) 
     * Camera (live video feed, rakam, benda yg camera buat la)
     * GPS (Global Positioning System)
      
## Radio      
* RX (Hanya bermaksud receiver, tapi yg dlm vid tu dia                           tulis Radio receiver)
* TX (Ni aku tambah. Based on RX, korg bole amik sebagai Radio Transmitter la)
   * VTX (Video Transmitter. Bole bersumber dri camera. Tbh dlm pendapat aku, bole gak guna hantar benda lain mcm koordinat GPS, kelajuan, altitude dll. Dah nama pun TX)
      * Frequency VTX: 5 - 8 Ghz. Bergantung kepada drone, nak pakai frequency mna2 pun bole. Klu nak try transmit kat frequency TV analog tu pon bole tapi klu x silap bole kacau frequency 5G.
       * Radio controller (Pengendali jarak jauh) Controller akan control drone guna frequency 2.4GHz, receive signal video VTX guna 5 - 8 GHz.
        * Keep in mid benda radio ni perlukan kelulusan dari pihak berkuasa di negara masing-masing. Kat Malaysia, pihak berkuasa tu MCMC. Macam klu kau nk beli handphone dri negara lain.

## Pergerakan (Movements)
* Motor
  * Jenis-jenis:
    * Brushed (low rotation speed, low endurance, low efficiency, low output power, **low cost**, higher maintenance, noisy, doesn't need ESC)
    *   Brushless (high rotation speed, high endurance, high efficiency, high output power, higher cost, low maintenance, quieter, needs ESC)
 * ESC
     * Electronic Speed Controller
      * Faktor pemilihan ESC:
          * Saiz motor
           * Saiz propeller
            * Kuasa bateri

## Bateri
 Nampak cam dorg pilih Li-Po (Lithium Polymer) jadi aq akan letak point nya:
 * 4S = 4 cell
   * 1 cell:
    * Minimum voltage: 3.7v
    * Maximum voltage: 4.2v
  * 4 cell:
    * Minimum voltage: 14.8v
    * Maximum voltage: 16.8v
* Pros and cons:
  * Pros
    * Ringan
    * Kapasiti tinggi
    * Boleh dicas semula
    * Bleh discas/cas dengan laju
  * Cons
     * Mudah letup
     * Jangka hayat pendek
     * Mahal oooo

## Frame/rangka drone
* Fungsi
   * Tapak pemasangan komponen
   * Melindungi komponen drone
* Ciri utama rangka
  * Ringan
  * Kekuatan badan
* Contoh bahan rangka
  * Carbon fiber
  * Aluminium
  * Plastik

## Sebab-sebab pakai sensor kat drone:
* Mengawal keseimbangan
* Kestabilan
* Keselamatan
