# ПРОСТОЮВАННЯ РЕСУРСІВ, АКТУАЛЬНІСТЬ ПИТАННЯ, ІСНУЮЧІ ПІДХОДИ ДЛЯ ВИРІШЕННЯ.

## Огляд проблеми ефективного використання обчислювальних ресурсів та актуальності досліджень.

Простої комп'ютерної техніки в корпоративній мережі приносять збитки компаніям та організаціям. Ефективне використання обчислювальних ресурсів під час простою комп'ютерних пристроїв дозволить компанії надавати свої «вільні» потужності для наукових та корпоративних обчислень.

## Існуючі підходи кластеризації та спільного управління обчислювальними ресурсами.

### Стаціонарні кластери

Переважно це кілька незалежних комп'ютерів, які використовуються разом і працюють як одна система для вирішення певних завдань, наприклад, для підвищення продуктивності, забезпечення надійності, спрощення адміністрування тощо.

![data-center](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ19XGolZrsR0MTEsYnEO5gcYbgtDwg_4xqEA&usqp=CAU)

### Ґрід-системи персональних комп'ютерів (ҐСПК)

Датаґрід - це географічно розподілена інфраструктура, до якої користувач може отримати доступ з будь-якого місця, незалежно від того, де він знаходиться. Сітка забезпечує колективний розподілений режим доступу до ресурсів та пов'язаних з ними послуг у межах глобально розподілених організацій (підприємств, що діляться глобальними ресурсами, базами даних, спеціалізованим програмним забезпеченням).

![grid](https://www.researchgate.net/profile/Basappa-Kodada/publication/268003683/figure/fig1/AS:295336758267909@1447425178906/Generic-view-of-Grid-Cluster-Computing-Environment.png)

### Desktop Grid корпоративного рівня

Одним із перспективних напрямків створення Desktop Grid є впровадження розподілених обчислювальних технологій в межах локальних комунікаційних мереж підприємств та організацій - Desktop Grid корпоративного рівня або Enterprise Desktop Grid. Цей підхід може дозволити приватній компанії отримати необхідні обчислювальні потужності без значних вкладень в обладнання та інфраструктуру.

### Програмні рішення дляв олонтерських обчислень

Класичні системи, такі як BOINC (Berkeley Open Infrastructure for Network Computing) - це незалежна гілка системи розвитку Grid. Волонтерські обчислення - це тип розподілених обчислень, при якому люди переносять невикористані ресурси своїх комп'ютерів на дослідницький проект (рисунок 1.5). Спеціальний агент встановлюється на користувацьке обладнання і виконує задані обчислення.

![volonteer-comps](https://www.researchgate.net/profile/Haitham-Barkallah/publication/319352828/figure/fig10/AS:669641902931976@1536666479233/Volunteer-Computing-Nowadays-volunteer-computing-provides-Petaflops-of-processing-power.png)

## Висновок

З поміж розглянутих підходів Grid кластер корпоративного рівня найближче відповідає поставленим вимогам, серед яких найголовнішими є гетерогенність, мобільність обчислювальних пристроїв та гнучкість у налаштуванні.
Обчислювальними вузлами будуть не стаціонарні, а запозичені на певний час пристрої, що призведе до динамічного розподілу потенційних ресурсів. Це можуть бути пристрої інтернету речей, мобільні пристрої або ноутбуки на ряду з класичними стаціонарними комп'ютерами.

Проте, Grid система має ряд недоліків з точки зору налаштування та підтримки отриманої мережі, тому було прийнято рішення про проектування гібридної кластерної системи, у якої буде усунуто згадані проблеми.