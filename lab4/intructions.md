## Подготовка
1. Перейти на страницу: [https://www.rcsb.org/structure/1EEH](https://www.rcsb.org/structure/1EEH)
2. Нажать **Download Files → PDB Format (Legacy PDB)**.
---

## 1. Wireframe
1. **File → Open → 1EEH.pdb** 
2. **Actions → Atoms/Bonds → wire** (каркасная модель)  
3. Сохранить изображение: **wireframe.png**

---

## 2. Backbone
1. Перезапустить модель (**close session**)
2. **Select → Structure → backbone only**  
3. **Actions → Atoms/Bonds → stick**  
4. Сохранить изображение: **backbone.png**

---

## 3. Spacefill
1. Перезапустить модель 
2. **Actions → Atoms/Bonds → sphere**   
3. Сохранить изображение: **spacefill.png**

---

## 4. Ribbons
1. Перезапустить модель
2. **Actions → Ribbon → show**  
3. Убрать атомы: **Actions → Atoms/Bonds → hide**  
4. Сохранить изображение: **ribbons.png**

---

## 5. Molecular surface
1. Перезапустить модель
2. **Actions → Surface → show**  
3. Сохранить изображение: **surface.png**

---

## 6. Раскраска — CPK
1. Перезапустить модель
2. Выбрать любое представление (например, Wireframe)  
3. **Actions → Color → by element**  
4. Сохранить изображение: **color_cpk.png**

---

## 7. Раскраска по доменам / цепям 

1. Перезапустить модель 
2. Для раскраски отдельных цепей:
   - **Select → Chain → A**  
     → **Actions → Color → red**   
3. Для окраски отдельного домена или диапазона резидов:
   - **Select → Residue → ALA**  
     → **Actions → Color → green**  
4. Сохранить изображение: **domains.png**

---

## 8. Изображение публикационного качества
1. Перезапустить модель 
2. Выбрать представление **Ribbons + Surface (частично прозрачная поверхность)**  
3. Настройки:  
   - Фон: **Actions → Color → all options → background → white**  
   - Прозрачность поверхности: **Actions → Surface → transparency ≈ 30%**     
4. Сохранить изображение: **File → Save Image → publication.png**