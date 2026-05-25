# 12. Sınıf Trig-2: Trigonometrik Denklemler

## Temel Denklem Türleri

### cos(x) = cos(α)
```
x = α + k·2π   veya   x = −α + k·2π      (k ∈ ℤ)
```
**Genel:** cos f(x) = cos g(x) →
  f(x) = g(x) + k·2π   veya   f(x) = −g(x) + k·2π

### sin(x) = sin(α)
```
x = α + k·2π   veya   x = π − α + k·2π   (k ∈ ℤ)
```
**Genel:** sin f(x) = sin g(x) →
  f(x) = g(x) + k·2π   veya   f(x) = π − g(x) + k·2π

### tan(x) = tan(α)
```
x = α + k·π   (k ∈ ℤ)
```
**Genel:** tan f(x) = tan g(x) →  f(x) = g(x) + k·π

### cot(x) = cot(α)
```
x = α + k·π   (k ∈ ℤ)
```

## Sık Kullanılan Dönüşümler
- sin → cos: sin x = cos(90°−x) → cos denklemi haline getir
- sec x = 2 → cos x = 1/2 → cos denklemi

## Klasik Denklemler: a·sinx + b·cosx = c

**Çözüm yöntemi:**
1. b'ye böl: (a/b)·sinx + cosx = c/b
2. tan θ = a/b olarak tanımla (θ açısını bul)
3. sin(x+θ) veya cos(x−θ) biçiminde yaz
4. Standart denklemi çöz

**Çözümün var olma koşulu:** c² ≤ a² + b²
Yani: |c| ≤ √(a²+b²)

**Değer aralığı:** f(x) = m·sinx + n·cosx ∈ [−√(m²+n²), √(m²+n²)]

## Homojen Trigonometrik Denklemler
f(sinx, cosx) = 0 formunda, sinx ve cosx'in dereceleri eşitse:
1. Her iki tarafı cos^n(x)'e böl
2. Yalnızca tan(x) içeren cebirsel denkleme dönüştür
3. Çöz

**Örnek:** sin²x − 2cosx·sinx − 8cos²x = 0
→ cos²x'e böl: tan²x − 2tanx − 8 = 0
→ (tanx−4)(tanx+2) = 0 → tanx = 4 veya tanx = −2

## Denklem Çözümünde Dikkat Edilecekler
- Paydada sıfır olan değerleri eleme
- Belirli aralıkta kaç kök var: sayısı bul, listeleyebilirsen listele
- Derece modu ile radyan modunu karıştırma
- sinx = a için |a| > 1 ise çözüm yok

## Trigonometrik Eşitsizlikler
Birim çember üzerinde yayı belirle, koşulu sağlayan aralığı oku.
