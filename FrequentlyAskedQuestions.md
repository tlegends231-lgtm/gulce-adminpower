# Sıkça Sorulan Sorular (SSS) - Gulce AdminPower

## 1. Bu datapack hangi sürümlerle uyumlu?
Gulce AdminPower, Minecraft 1.21 ve üzeri sürümlerle uyumludur.  
Eski sürümlerde bazı fonksiyonlar çalışmayabilir.

## 2. Kurulum nasıl yapılır?
1. Depoyu indir: [GitHub](https://github.com/tlegends231-lgtm/gulce-adminpower)
2. `.minecraft/saves/<world>/datapacks/` içine kopyala
3. Oyunda `/reload` komutunu kullan

## 3. GUI açılmıyor, ne yapmalıyım?
- Datapack yüklendi mi kontrol et (`/datapack list`)  
- Minecraft sürümü 1.21.6+ olmalı  
- Server üzerinde yeterli permission seviyen olmalı

## 4. Macro nasıl eklenir?
- `$<komut> $(Macro1) $(Macro2) $(Macro4)` ile kendi makronu oluştur (*.mcfunction gerekli)
- `$tp $(xyz)` veya `$say $(msg)` gibi parametreler destekleniyor
- Çalıştırma `/function <id> <args>` veya `/function <id> with <source> <value>`

## 5. Yetki / Permission ayarları nasıl yapılır?
- `/function custom:permissions/<izin>/init <args>` kullan
- Daha sonra fonksiyonlar, tag ve scoreboard ile yetki yönetimi sağlanır