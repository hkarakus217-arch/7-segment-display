# 7-segment-display
7 segment display (yedi segment gösterge), elektronik projelerde en çok karşılaşılan temel bileşenlerden biridir. Adından da anlaşılacağı gibi, 0'dan 9'a kadar rakamları ve bazı harfleri gösterebilen, yedi adet ışık yayan diyot (LED) segmentinden oluşur. Bu segmentlerin her birini açıp kapayarak farklı kombinasyonlar oluşturulur ve böylece istenilen rakam veya harf ekranda belirir.
Bir 7 segment display, yedi ana segmentten (a, b, c, d, e, f, g) ve genellikle bir ondalık nokta (DP - Decimal Point) segmentinden oluşur.
Rakamları Oluşturma: Ekranda "1" rakamını görmek istediğinde, sadece b ve c segmentleri yanar. "8" rakamı için ise tüm segmentlerin yanması gerekir. Hangi segmentin yanacağını sen belirleyerek ekranda istediğin rakamı oluşturursun.
Bu sayıları binary olarak ya da hex decimal olarak da yazıdıra biliriz.
1 =segmentte olarsa b ve c segmentleri ile yakarız.
    binary olarak yakmak istersek 0xb00000110 olur.
    hexdecimal olacak olursa 0x06 olur.
8 =segmentte olarsa tüm segmentleri ile yakarız.
    binary olarak yakmak istersek 0xb01111111 olur.
    hexdecimal olacak olursa 0x7F  olur.
 
