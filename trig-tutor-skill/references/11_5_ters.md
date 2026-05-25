# 11. Sınıf Trig-5: Ters Trigonometrik Fonksiyonlar

## Tanımlar ve Aralıklar

| Fonksiyon | Tanım Kümesi | Değer Aralığı | Kısaca |
|-----------|-------------|--------------|--------|
| arcsin x  | [−1, 1]     | [−π/2, π/2]  | sinx=y ⟺ x=arcsiny |
| arccos x  | [−1, 1]     | [0, π]       | cosx=y ⟺ x=arccosy |
| arctan x  | ℝ           | (−π/2, π/2)  | tanx=y ⟺ x=arctany |
| arccot x  | ℝ           | (0, π)       | cotx=y ⟺ x=arccosy |

## Temel Değerler
| x | arcsin x | arccos x | arctan x |
|---|---------|---------|---------|
| −1 | −π/2 | π | — |
| −√3/2 | −π/3 | 5π/6 | — |
| −√2/2 | −π/4 | 3π/4 | — |
| −1/2 | −π/6 | 2π/3 | — |
| 0  | 0    | π/2  | 0 |
| 1/2 | π/6 | π/3 | — |
| √2/2 | π/4 | π/4 | — |
| √3/2 | π/3 | π/6 | — |
| 1  | π/2  | 0    | — |
| √3 | —    | —    | π/3 |
| −1 | —    | —    | −π/4 |

## Önemli Özdeşlikler
- arcsin(x) + arccos(x) = π/2
- arctan(x) + arccot(x) = π/2
- arcsin(−x) = −arcsin(x)  [tek fonksiyon]
- arccos(−x) = π − arccos(x)

## Bileşik İfadeler
- cos(arcsin(x)) = √(1−x²)   (x ∈ [−1,1])
- sin(arccos(x)) = √(1−x²)   (x ∈ [−1,1])
- tan(arcsin(x)) = x/√(1−x²)
- sec(arctan(x)) = √(1+x²)

## Ters Fonksiyon Bulma
f(x) = a + b·arcsin(cx + d) için f⁻¹:
1. y = a + b·arcsin(cx + d) yaz
2. (y−a)/b = arcsin(cx+d)
3. sin((y−a)/b) = cx + d
4. x = [sin((y−a)/b) − d] / c  → f⁻¹(x) elde edilir

## Tanım Kümesi Belirleme
f(x) = arcsin(g(x)) tanımlı ⟺ −1 ≤ g(x) ≤ 1
f(x) = arccos(g(x)) tanımlı ⟺ −1 ≤ g(x) ≤ 1
