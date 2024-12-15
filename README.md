# scRNA-Seq_project

Влияние метода батч-коррекции на итоговую кластеризацию клеток при секвенировании одиночных клеток (single-cell RNA-Seq)

**Тема проекта:** Проверка различных программ для батч-коррекции на устойчивость к овер-коррекции батч-эффекта

**Задача:** 

      - Искуственно создать два батча, состоящих из (а) абсолютно разных и (б) частично перекрывающихся типов клеток и выполнить батч-коррекцию тремя методами (Harmony, bbknn и PyCombat)
      - Охарактеризовать стабильность каждого метода к овер-коррекции батч-эффекта
