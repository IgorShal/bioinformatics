# Лабораторная работа: Предсказание и выравнивание белковой структуры

## 1. Последовательность и используемые программы

**Последовательность белка :**


MDKGDVTALPMKKWFTTNYHYLVPEVEPSAEIKLNSTKPFDEFNEAKSLGVETKPVFIGPYTFLKLARTPEAAELEIDKGLVNAVAAVYAEVLARFNDLG


**Программы-предсказатели структуры:**

- **ESMFold** (Colab notebook)  
- **AlphaFold2** (Colab notebook)  

**Программа выравнивания структур:**

- **RCSB Pairwise Structure Alignment (jFATCAT-Flexible)** 

---

## 2. Полученные ноутбуки

- `Shalygin_ESMFold.ipynb`  
- `Shalygin_lab5_AlphaFold2.ipynb`  


---

## 3. Полученные предсказания структур (PDB)

- `predictions\esm_fold_prediction.pdb`  
- `predictions\Prediction_6e0f8_unrelaxed_alphafold_2.pdb`  

---

## 4. Полная выдача программы выравнивания

- `alignment_output\esm_fold_prediction.pdb.A.cif`  
- `alignment_output\molstar-model.glb`  
- `alignment_output\Prediction_6e0f8_unrelaxed_alphafold_2.pdb.A.cif`  
- `alignment_output\sequence_alignment_2025-11-21-19-42-8.fasta`  
- `alignment_output\transformation_matrices_2025-11-21-19-42-8.json`


> Примечание: RCSB не предоставил PDB-файл выравнивания, поэтому для визуализации использовались исходные PDB модели.

---

## 5. Проект/сессия программы визуализации

- `alignment_session.pse` (PyMOL сессия с наложением ESMFold и AlphaFold2)
- Также ссылка на [визуализацию](https://www.rcsb.org/alignment?request-body=eJyVj81qAzEMhN9F5y2klJbiW5%2BjBKPYUmLwz1aWyYZl371yC733JmZG%2BkY7fA2SB7gd2qqp1T5HIR1SfSczayAfUREcY%2B50LBBaVdp0BkuLBA5WTHJPnWCBQnprcXoVy%2FQYNaA%2BcaYtXfKMrChmKckvq%2FTow9DGDO5lAeTVx9T1T3t%2BO50WYMFroao%2BU73qDdy7sXDzdRSvxlY79npYu64ygtUnEz534CYFdXaMF2N3yhTmnxON%2FVF8srLwAbb6n%2FB5ojjlH8r5%2BAaLk3Kb&response-body=eJzNVdlO40gU%2FRc%2F20ntS96swWFQEiZqoowQQlbZLgdLXtJeaBDi3%2BeWwxJawPQyD6MkUurWuecudW7Vg1fUeePNHrxhKDJv5qmMJoYxGkgtVMCkJIFhOA1SkSY8MWmCaeL5XtebfugA%2F8dfq%2FUy2kTeo%2B9VtjeOypTFrq5s3cdVk1kA7U3Rfis6C45He7a%2FaVzI3PSp6YO8tHdFUlrH1NpuKHvgv3qAUO2Q9gOYxuXQluBz0%2Ff7bjadDp1tg2FfNiabtGmXTJp2N73F06z5VjvjNMks1ijPA2FwHjDE80Bxq4KcpVKYjLOcq6ntqjhvyizetzYr0r5o6kmSFjnkmzdtZXqIWFUHQ9HFSVGb9t6bQWLW92pTuRrf49hnY69sacf12JvuvorHTofe46P%2F0%2FUIZIzObBroXKGAYYQDRVITEEGVZjrNrRHT9UsKsbAoV%2FFQt7Y0dzaLTbm%2FMWOe5KdL%2FEHaf6362n891PhFEOPptnYHLu6kr956%2BV5id3Fnv44GdVgWdWbvvBnyvdLWu%2F7Gmwnievqxo8RvPAV%2FdaUIEvs0qvgoKkafR8Vv88Xk1ZX%2FXsLQyr41dXc4w%2BfWYR89fd79B2UGaMIFF4hwLamiTBPhowlSmFKhCBZEEYkJ8QGnCBJcIqEQpkxwDQxglSA9LSRXghGspXY2poTginNMlJYAlkDJBOGUMy6kUgA%2BOFOBnSfmSmpOiaQAVAJYJGdKIYol5WCilHNKAcIxp1gz50wmghJNuBSKSsGwHPkkp1JiwYAYvsIP8IQiDJQUQ00IacygbKe7oapGYcO9kjbPd8qtKQcQOEEKqKCj93sn966oitK0RX8fjFjPndQTlE4UfwF%2BWV2ceE7VNai5joG1yAYbu1sP%2BDU5KN5%2BHWydfi%2F4ZzPQrE4WpyfbTbhcrxaLv%2Bebzfnln5fL7TraRuuLMDpbLM8vNov1%2FCSan0fh4mJ5uo1gvZ2fna4vN%2FPlYhl%2B2ayjMIyW0RlwLbfn4TYMt5dhtIWt%2BfnJ8tTzj0bslybsN7SuqGvEzuwPwY9RRwHI47WL8H9tzIeXgOaQ%2BH8oMRgJ%2FQp86kZQZKAcwL8VI2LfifGYRqiXzc3qvTjvhHlN7DNhuw33xJfwAjxtumph4Hz4HUQ%2FekKPXIPc81%2FHaXNrW7ODeFdAock1zMfjP11lqC0%3D&encoded=true)

---

## 6. Снимки экрана

- Папка `screenshots/` содержит скриншоты выравнивания с разными цветами цепей:
  - ESMFold – красный  
  - AlphaFold – синий  

---

## 7. Краткие выводы

- Предсказанные структуры ESMFold и AlphaFold2 почти полностью совпадают по общей форме и топологии.  
- Основные α-спирали и β-листы накладываются друг на друга с минимальным расхождением.  
- Отличия наблюдаются только в гибких петлях , что ожидаемо для предсказаний на основе последовательности.  
- RMSD при выравнивании через jFATCAT-Flexible показывает высокое сходство, подтверждая корректность предсказаний.  
- Оба метода дают надёжное представление о третичной структуре данного белка.
