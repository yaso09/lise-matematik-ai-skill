# 11. Sınıf Trig-4: Periyot ve Grafikler

## Periyodik Fonksiyon
f(x + T) = f(x) koşulunu sağlayan en küçük pozitif T'ye **esas periyot** denir.

## Temel Periyotlar
| Fonksiyon | Esas Periyot |
|-----------|-------------|
| sinx, cosx | 2π |
| tanx, cotx | π |

## Bileşik Fonksiyonlarda Periyot

### f(x) = a + b·sinᵐ(px + q) veya a + b·cosᵐ(px + q)
```
m tek  → T = 2π / |p|
m çift → T = π / |p|
```

### f(x) = a + b·tanᵐ(px + q) veya a + b·cotᵐ(px + q)
```
T = π / |p|   (m'den bağımsız)
```

## Toplam Fonksiyonun Periyodu
f(x) = g(x) ± h(x) ise:
```
T_f = EKOK(T_g, T_h)
```

**EKOK hesabı kesirli periyotlar için:**
```
EKOK(a/b, c/d) = EKOK(a,c) / EBOB(b,d)
```

## Grafik Çizim Adımları
1. Esas periyodu bul
2. [0, T] aralığında değişim tablosu yap
3. Kritik noktaları işaretle (max, min, sıfır geçişleri)
4. Grafiği çiz; periyot boyunca tekrarla

## f(x) = a·sin(bx + c) + k Parametreleri
| Parametre | Etkisi |
|-----------|--------|
| \|a\| | Genlik (max−min = 2\|a\|) |
| b | Periyot = 2π/\|b\| |
| c | Yatay kaydırma (faz) |
| k | Dikey kaydırma |
