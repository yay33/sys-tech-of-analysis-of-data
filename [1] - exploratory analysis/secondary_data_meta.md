1. Title: Secondary mushroom data

2. Sources:
	(a) Mushroom species drawn from source book:
		Patrick Hardin.Mushrooms & Toadstools.
	    Zondervan, 1999
	(b) Inspired by this mushroom data:
		Jeff Schlimmer.Mushroom Data Set. Apr. 1987.
		url:https://archive.ics.uci.edu/ml/datasets/Mushroom.
	(c) Repository containing the related Python scripts and all the data sets: https://mushroom.mathematik.uni-marburg.de/files/ 
	(d) Author: Dennis Wagner
	(e) Date: 05 September 2020

3. Relevant information:
	This dataset includes 61069 hypothetical mushrooms with caps based on 173 species (353 mushrooms
	per species). Each mushroom is identified as definitely edible, definitely poisonous, or of 
	unknown edibility and not recommended (the latter class was combined with the poisonous class).
	Of the 20 variables, 17 are nominal and 3 are metrical.

4. Data simulation:
	The related Python project (Sources (c)) contains a Python module secondary_data_generation.py
	used to generate this data based on primary_data_edited.csv also found in the repository.
	Both nominal and metrical variables are a result of randomization.
	The simulated and ordered by species version is found in secondary_data_generated.csv.
	The randomly shuffled version is found in secondary_data_shuffled.csv.

5. Class information: (Информация о классах)  
  1. class: (класс)  
    - poisonous=p (ядовитый=p),  
    - edible=e (съедобный=e) (binary) (двоичный)  

6. Variable Information: (Информация о переменных)  
   (n: номинальный, m: метрический; номинальные значения как наборы значений)  
   1. cap-diameter (m): (диаметр шляпки (м)):  
       - float number in cm (число с плавающей запятой в см)  
   2. cap-shape (n): (форма шляпки (н)):  
      - bell=b (колокольчик=b),  
      - conical=c (конусообразный=c),  
      - convex=x (выпуклый=x),  
      - flat=f (плоский=f),  
      - sunken=s (вогнутый=s),  
      - spherical=p (сферический=p),  
      - others=o (другие=o)  
   3. cap-surface (n): (поверхность шляпки (н)):  
      - fibrous=i (волокнистый=i),  
      - grooves=g (бороздчатый=g),  
      - scaly=y (чешуйчатый=y),  
      - smooth=s (гладкий=s),  
      - shiny=h (блестящий=h),  
      - leathery=l (кожистый=l),  
      - silky=k (шелковистый=k),  
      - sticky=t (липкий=t),  
      - wrinkled=w (морщинистый=w),  
      - fleshy=e (мясистый=e)  
   4. cap-color (n): (цвет шляпки (н)):  
      - brown=n (коричневый=n),  
      - buff=b (рыжевато-коричневый=b),  
      - gray=g (серый=g),  
      - green=r (зеленый=r),  
      - pink=p (розовый=p),  
      - purple=u (фиолетовый=u),  
      - red=e (красный=e),  
      - white=w (белый=w),  
      - yellow=y (желтый=y),  
      - blue=l (синий=l),  
      - orange=o (оранжевый=o),  
      - black=k (черный=k)  
   1. does-bruise-bleed (n): (образует ли синяки или кровоточит (н)):  
      - bruises-or-bleeding=t (синяки или кровотечение=t),  
      - no=f (нет=f)  
   2. gill-attachment (n): (прикрепление пластинок (н)):  
      - adnate=a (прирастающий=a),  
      - adnexed=x (придаточный=x),  
      - decurrent=d (нисходящий=d),  
      - free=e (свободный=e),  
      - sinuate=s (изогнутый=s),  
      - pores=p (поры=p),  
      - none=f (нет=f),  
      - unknown=? (неизвестно=?)  
   3. gill-spacing (n): (расстояние между пластинками (н)):  
      - close=c (близко=c),  
      - distant=d (дистанционно=d),  
      - none=f (нет=f)  
   4. gill-color (n): (цвет пластинок (н)):  
      - see cap-color + none=f (см. цвет шляпки + нет=f)  
   5. stem-height (m): (высота стебля (м)):  
      - float number in cm (число с плавающей запятой в см)  
   6. stem-width (m): (ширина стебля (м)):  
      - float number in mm (число с плавающей запятой в мм)  
   7. stem-root (n): (корень стебля (н)):  
      - bulbous=b (луковичный=b),  
      - swollen=s (увеличенный=s),  
      - club=c (буловидный=c),  
      - cup=u (чашеобразный=u),  
      - equal=e (равный=e),  
      - rhizomorphs=z (ризоморфные=z),  
      - rooted=r (укоренившийся=r)  
   8. stem-surface (n): (поверхность стебля (н)):  
      - see cap-surface + none=f (см. поверхность шляпки + нет=f)  
   9. stem-color (n): (цвет стебля (н)):  
      - see cap-color + none=f (см. цвет шляпки + нет=f)  
   10. veil-type (n): (тип покрывала (н)):  
      - partial=p (частичный=p), universal=u (универсальный=u)  
   11. veil-color (n): (цвет покрывала (н)):  
      - see cap-color + none=f (см. цвет шляпки + нет=f)  
   12. has-ring (n): (имеет ли кольцо (н)):  
      - ring=t (кольцо=t), none=f (нет=f)  
   13. ring-type (n): (тип кольца (н)):  
      - cobwebby=c (паутина=c),  
      - evanescent=e (исчезающий=e),  
      - flaring=r (расширяющийся=r),  
      - grooved=g (бороздчатый=g),  
      - large=l (большой=l),  
      - pendant=p (вертикальный=p),  
      - sheathing=s (обёрточный=s),  
      - zone=z (зонный=z),
      - scaly=y (чешуйчатый=y),  
      - movable=m (подвижный=m),  
      - none=f (нет=f),  
      - unknown=? (неизвестно=?)  
   14. spore-print-color (n): (цвет спорового отпечатка (н)):  
      - see cap color (см. цвет шляпки)  
   15. habitat (n): (местообитание (н)):  
      - grasses=g (травы=g),  
      - leaves=l (листья=l),  
      - meadows=m (лужайки=m),  
      - paths=p (тропинки=p),  
      - heaths=h (вересковые пустоши=h),  
      - urban=u (городской=u),  
      - waste=w (пустошь=w),  
      - woods=d (лес=d)  
   16. season (n): (сезон (н)):  
      - spring=s (весна=s),  
      - summer=u (лето=u),  
      - autumn=a (осень=a),  
      - winter=w (зима=w)  

