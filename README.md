# KiCAD LM2596 Buck Regulator Project

Bu projede giriş gerilimini düşürerek çıkışa aktarmak amaçlanmıştır. Giriş gerilimini düşüren bu tip devrelere SMPS (Switched-Mode Power Supply) devreleri denilmiş olup, bu proje özelinde LM2596-ADJ entegresi kullanılmıştır. 

Çıkıştaki ani akım ihtiyacını karşılayabilmek ve voltaj çakılmasını engelleyebilmek için giriş kısmında 50V dayanımlı iki tane 470 uF'lık polarize kondansatör kullanılmıştır. Anahtarın açık olduğu esnada yük üzerindeki akımı kaybetmemek amacıyla endüktans 68 uH olarak seçilmiş olup, devreden geçecek olan maksimum akımın 3A düzeyinde olması planlandığından ters yön diyotu Schottky (5A) olarak seçilmiştir. Ayrıca yükün üstündeki gerilimin ripple (dalgalanma) katsayısının düşürülmesi amacıyla çıkışa paralel bağlı olan iki tane 220 uF'lık 35V dayanımlı polarize kondansatör kullanılmıştır.


📊 LTspice Simülasyon Sonucu
<img width="1420" height="1034" alt="Screenshot 2026-07-05 162005" src="https://github.com/user-attachments/assets/d16979c5-73db-42d9-98fb-33cb505e72aa" />


📊 PCB İlk Bakış
<img width="1217" height="722" alt="Screenshot 2026-07-07 082113" src="https://github.com/user-attachments/assets/b99203e2-5612-4efd-aae2-95b01a374e39" />

