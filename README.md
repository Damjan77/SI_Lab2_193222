# SI_Lab2_193222

2)
![image](https://user-images.githubusercontent.com/80587900/119867640-62a77d80-bf1e-11eb-892a-372be367e4a1.png)
 

3) Цикломатска комплексност = 8
Цикломатската комплекснот ја добив така што ги изброив регионите на графот. Имам 8 региони. Исто така може да се добие и со формулата E-V + 2  (ребра – темиње + 2).
Може да се добие и со Предикатни јазли (јазли каде што има разгранување). Во графот има 7 предикатни јазли по што следува 7+1 = 8.

4) Тест случаи според критериумот multiple condition:
if (hr < 0 || hr > 24)
TX
FT
FF

if (min < 0 || min > 59)
TX
FT
FF

if (sec >= 0 && sec <= 59)
TT
TF
FX

if(hr == 24 && min == 0 && sec == 0)
TTT
TTF
TFX
FXX

Тест случаи:
![image](https://user-images.githubusercontent.com/80587900/119868084-e5c8d380-bf1e-11eb-85ec-86ddddbcdfcd.png)
5) Тест случаи според Every branch
![image](https://user-images.githubusercontent.com/80587900/119868209-0db83700-bf1f-11eb-90d0-a1a3293dc815.png)




