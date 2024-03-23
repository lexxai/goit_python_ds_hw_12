# Модуль 12. Основи NLP.

*З циклу [домашніх завдань Python Data Science](https://github.com/lexxai/goit_python_data_sciense_homework).*

# Домашнє завдання

Зробіть summary нижчевказаного тексту використовуючи бібліотеки для NLP: `nltk` та `SpaCy`

```
The Orbiter Discovery, OV-103, is considered eligible for listing in the National Register of Historic Places (NRHP) in the context of the U.S. Space Shuttle Program (1969-2011) under Criterion A in the areas of Space Exploration and Transportation and under Criterion C in the area of Engineering. Because it has achieved significance within the past fifty years, Criteria Consideration G applies. Under Criterion A, Discovery is significant as the oldest of the three extant orbiter vehicles constructed for the Space Shuttle Program (SSP), the longest running American space program to date; she was the third of five orbiters built by NASA. Unlike the Mercury, Gemini, and Apollo programs, the SSP’s emphasis was on cost effectiveness and reusability, and eventually the construction of a space station. Including her maiden voyage (launched August 30, 1984), Discovery flew to space thirty-nine times, more than any of the other four orbiters; she was also the first orbiter to fly twenty missions. She had the honor of being chosen as the Return to Flight vehicle after both the Challenger and Columbia accidents. Discovery was the first shuttle to fly with the redesigned SRBs, a result of the Challenger accident, and the first shuttle to fly with the Phase II and Block I SSME. Discovery also carried the Hubble Space Telescope to orbit and performed two of the five servicing missions to the observatory. She flew the first and last dedicated Department of Defense (DoD) missions, as well as the first unclassified defense-related mission. In addition, Discovery was vital to the construction of the International Space Station (ISS); she flew thirteen of the thirty-seven total missions flown to the station by a U.S. Space Shuttle. She was the first orbiter to dock to the ISS, and the first to perform an exchange of a resident crew. Under Criterion C, Discovery is significant as a feat of engineering. According to Wayne Hale, a flight director from Johnson Space Center, the Space Shuttle orbiter represents a “huge technological leap from expendable rockets and capsules to a reusable, winged, hypersonic, cargo-carrying spacecraft.” Although her base structure followed a conventional aircraft design, she used advanced materials that both minimized her weight for cargo-carrying purposes and featured low thermal expansion ratios, which provided a stable base for her Thermal Protection System (TPS) materials. The Space Shuttle orbiter also featured the first reusable TPS; all previous spaceflight vehicles had a single-use, ablative heat shield. Other notable engineering achievements of the orbiter included the first reusable orbital propulsion system, and the first two-fault-tolerant Integrated Avionics System. As Hale stated, the Space Shuttle remains “the largest, fastest, winged hypersonic aircraft in history,” having regularly flown at twenty-five times the speed of sound.
```
# Виконання

[goit_python_ds_hw_12.ipynb](goit_python_ds_hw_12.ipynb)

[Colab goit_python_ds_hw_12.ipynb](https://colab.research.google.com/drive/141FBlMlDloes-qr6M8v3IQcblJ7HjHQO?usp=sharing)



# Висновок
Завдання було на онсові тексту створити короткий зміст цього тексту. 

Для фрмування короткого тексту було вибрано було 4 речення, на основі частоти вживання слів у цих реченях.

В результаті роботи було викорисанно декілька підходів з викорисатнням різних бібліотек `nltk` та `spaCy`.

В результаті було отрманно однаковий результат summary з 4-х речень:

```
The Orbiter Discovery, OV-103, is considered eligible for listing in the National Register of Historic Places (NRHP) in the context of the U.S. Space Shuttle Program (1969-2011) under Criterion A in the areas of Space Exploration and Transportation and under Criterion C in the area of Engineering.
Under Criterion A, Discovery is significant as the oldest of the three extant orbiter vehicles constructed for the Space Shuttle Program (SSP), the longest running American space program to date; she was the third of five orbiters built by NASA.
In addition, Discovery was vital to the construction of the International Space Station (ISS); she flew thirteen of the thirty-seven total missions flown to the station by a U.S. Space Shuttle.
According to Wayne Hale, a flight director from Johnson Space Center, the Space Shuttle orbiter represents a “huge technological leap from expendable rockets and capsules to a reusable, winged, hypersonic, cargo-carrying spacecraft.
```

Переклад стислого змісту ситемою автоматичного прекладу DeepL:

```
Орбітальний корабель "Діскавері" (OV-103) вважається таким, що має право на внесення до Національного реєстру історичних місць (NRHP) в контексті Програми космічних човників США (1969-2011 рр.) за критерієм А в галузі космічних досліджень і транспорту та за критерієм С в галузі інженерії.
За критерієм А "Діскавері" має важливе значення як найстаріший з трьох збережених орбітальних кораблів, побудованих для програми "Спейс Шаттл" (SSP), найдовшої американської космічної програми на сьогоднішній день; вона була третім з п'яти орбітальних кораблів, побудованих NASA.
Крім того, "Діскавері" відіграла важливу роль у будівництві Міжнародної космічної станції (МКС); вона здійснила тринадцять з тридцяти семи польотів на станцію за допомогою американських шатлів.
За словами Вейна Хейла, керівника польотів Космічного центру імені Джонсона, орбітальний корабель "Спейс Шаттл" являє собою "величезний технологічний стрибок від одноразових ракет і капсул до багаторазового, крилатого, гіперзвукового, вантажного космічного корабля.
```
