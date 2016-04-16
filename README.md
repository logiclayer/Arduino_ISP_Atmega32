# Arduino'yu ISP'ye çevirerek Atmega32 programlanması
Arduino'yu ISP'ye çevirerek Atmega32 mikrodenetleyicisinin programlanmasını anlatıyorum.
Uygulanacak adımlar;

1. Arduino UNO’muzun bütün pinlerini boş hale getirip sadece USB ile bilgisayar bağlantısının olmasını sağlayın.
2. Arduino IDE’sinin bulunduğu klasörü bulup hardware\arduino\avr klasörüne geçip, (örneğin : C:\Program Files\Arduino\hardware\arduino\avr) boards.txt dosyasını bir text editör ile açıp en sonuna size linkini vermiş olduğum boards_eklenecekler.txt içindeki satırları ekleyin.
3. Arduino IDE’sinin bulunduğu klasörü bulup hardware\arduino\avr\variants klasörünün içine size linkini vermiş olduğum mega32 klasörünü kopyalayın.
4. Arduino IDE’yi açın.
5. File -> Examples > ArduinoISP’yi açın.
6. Tools -> Board : Arduino UNO ve Tools -> Programmer : AVR ISP mkII seçili olduğundan emin olun.
7. Sketch -> Upload şıkkını tıklayın ve upload işleminin bitmesini bekleyin.
8. Şemadaki Arduino UNO ile Atmega32 mikrodenetleyicisinin bağlantısını yapın.
9. File -> Examples -> Basics -> Blink sketchini açın.
10. Tools -> Board -> Atmega32-Internal 8Mhz şıkkını seçin, Tools -> Programmer -> Arduino as ISP şıkkını seçin.
11. Sketch -> Upload Using Programmer şıkkını tıklayarak sketchi Arduino üzerinden Atmega32’ye programlanmasını bekleyin.
