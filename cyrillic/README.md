# Raven Cyrillic
## Design
### Goals
1. As fast as possible for Russian.
2. Intuitive to non-native users, to reduce learning cost as much as possible.
3. Mostly compatible with Yasherty, so there's virtually no transition cost.

### Principles
1. Use single-letter mapping wherever possible.
2. Try to match the standard Romanizations of each Cyrillic letter.
3. Minimize finger travel distances on QWERTY keyboards in double key mappings.
4. Use stream breakers where single-letter mappings cause confusion.

## Keymap
| Keymap    | RU       | UK       | BE       | MN       | BG       | MK/BS... |
| --------- | -------- | -------- | -------- | -------- | -------- | -------- |
| `a`       | Аа (a)   | Аа (a)   | Аа (a)   | Аа (a)   | Аа (a)   | Аа (a)   |
| `b`       | Бб (b)   | Бб (b)   | Бб (b)   | Бб (b)   | Бб (b)   | Бб (b)   |
| `v vd ww` | Вв (v)   | Вв (w)   | Вв (v)   | Вв (v)   | Вв (v)   | Вв (v)   |
| `g gd hh` | Гг (g)   | Гг (h)   | Гг (x)   | Гг (g)   | Гг (g)   | Гг (g)   |
| `gg`      |          | Ґґ (g)   |          |          |          |          |
| `gh`      |          |          |          |          |          | Ѓѓ (ǵ)   |
| `d dq`    | Дд (d)   | Дд (d)   | Дд (d)   | Дд (d)   | Дд (d)   | Дд (d)   |
| `dd dz`   |          |          |          |          |          | Ђђ (dj)  |
| `е eh`    | Ее (ye)  | Ее (e)   | Ее (ye)  | Ее (ye)  | Ее (e)   | Ее (e)   |
| `je`      |          | Єє (ye)  |          |          |          |          |
| `yo`      | Ёё (yo)  |          | Ёё (yo)  | Ёё (yo)  |          |          |
| `zz zh`   | Жж (zh)  | Жж (zh)  | Жж (zh)  | Жж (zh)  | Жж (zh)  | Жж (zh)  |
| `z zd`    | Зз (z)   | Зз (z)   | Зз (z)   | Зз (z)   | Зз (z)   | Зз (z)   |
| `ds`      |          |          |          |          |          | Ѕѕ (dz)  |
| `i ih yy` | Ии (i)   | Ии (y)   |          | Ии (i)   | Ии (i)   |          |
| `ii yi`   |          | Іі (i)   | Іі (i)   |          |          | Ii (i)   |
| `ji`      |          | Її (yi)  |          |          |          |          |
| `j jh jy` | Йй (iy)  | Йй (iy)  | Йй (iy)  | Йй (iy)  | Йй (iy)  |          |
| `jj`      |          |          |          |          |          | Јј (ij)  |
| `k kd`    | Кк (k)   | Кк (k)   | Кк (k)   | Кк (k)   | Кк (k)   | Кк (k)   |
| `l ld`    | Лл (l)   | Лл (l)   | Лл (l)   | Лл (l)   | Лл (l)   | Лл (l)   |
| `lj lk`   |          |          |          |          |          | Љљ (lj)  |
| `m`       | Мм (m)   | Мм (m)   | Мм (m)   | Мм (m)   | Мм (m)   | Мм (m)   |
| `n nd`    | Нн (n)   | Нн (n)   | Нн (n)   | Нн (n)   | Нн (n)   | Нн (n)   |
| `nj nk`   |          |          |          |          |          | Њњ (nj)  |
| `o`       | Оо (o)   | Оо (o)   | Оо (o)   | Оо (o)   | Оо (o)   | Оо (o)   |
| `x`       |          |          |          | Өө (oo)  |          |          |
| `p`       | Пп (p)   | Пп (p)   | Пп (p)   | Пп (p)   | Пп (p)   | Пп (p)   |
| `r`       | Рр (r)   | Рр (r)   | Рр (r)   | Рр (r)   | Рр (r)   | Рр (r)   |
| `s sd`    | Сс (s)   | Сс (s)   | Сс (s)   | Сс (s)   | Сс (s)   | Сс (s)   |
| `t td`    | Тт (t)   | Тт (t)   | Тт (t)   | Тт (t)   | Тт (t)   | Тт (t)   |
| `tt tj`   |          |          |          |          |          | Ћћ (ć)   |
| `kk kj`   |          |          |          |          |          | Ќќ (ḱ)   |
| `u uh`    | Уу (u)   | Уу (u)   | Уу (u)   | Уу (u)   | Уу (u)   | Уу (u)   |
| `uu iu`   |          |          | Ўў (w)   |          |          |          |
| `vv uy`   |          |          |          | Үү (uu)  |          |          |
| `f`       | Фф (f)   | Фф (f)   | Фф (f)   | Фф (f)   | Фф (f)   | Фф (f)   |
| `h hd`    | Хх (kh)  | Хх (kh)  | Хх (kh)  | Хх (kh)  | Хх (kh)  | Хх (kh)  |
| `c cd`    | Цц (ts)  | Цц (ts)  | Цц (ts)  | Цц (ts)  | Цц (ts)  | Цц (ts)  |
| `cc ch`   | Чч (ch)  | Чч (ch)  | Чч (ch)  | Чч (ch)  | Чч (ch)  | Чч (ch)  |
| `dj dc`   |          |          |          |          |          | Џџ (dzh) |
| `ss sh`   | Шш (sh)  | Шш (sh)  | Шш (sh)  | Шш (sh)  | Шш (sh)  | Шш (sh)  |
| `w wd sw` | Щщ (sch) | Щщ (sch) |          | Щщ (sch) | Щщ (sch) |          |
| `qa`      | Ъъ (")   |          |          | Ъъ (")   | Ъъ (ǎ)   |          |
| `y yh yj` | Ыы (y)   |          | Ыы (y)   | Ыы (y)   |          |          |
| `qq`      | Ьь (')   | Ьь (')   | Ьь (')   | Ьь (')   | Ьь (y)   |          |
| `ee`      | Ээ (e)   |          | Ээ (e)   | Ээ (e)   |          |          |
| `yu`      | Юю (yu)  | Юю (yu)  | Юю (yu)  | Юю (yu)  | Юю (yu)  |          |
| `q qh ya` | Яя (ya)  | Яя (ya)  | Яя (ya)  | Яя (ya)  | Яя (ya)  |          |
| `qz`      |          | '        | '        |          |          |          |