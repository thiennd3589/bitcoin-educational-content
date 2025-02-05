---
name: COLDCARD Q - Advanced
description: Использование дополнительных опций COLDCARD Q
---
![cover](assets/cover.webp)

В предыдущем руководстве мы рассказали о начальной настройке COLDCARD Q и его основных функциях для начинающих. Если вы только что получили COLDCARD Q и еще не настроили его, я рекомендую вам начать с этого руководства, прежде чем продолжить здесь:

https://planb.network/tutorials/wallet/hardware/coldcard-q-73e86d1a-6fe6-4d8b-bb15-8690298020e3
Это новое руководство посвящено расширенным возможностям COLDCARD Q, предназначенным для опытных и параноидальных пользователей. На самом деле, COLDCARD отличается от других аппаратных кошельков множеством продвинутых функций безопасности. Конечно, вам не обязательно использовать все эти опции. Просто выберите те, которые соответствуют вашей стратегии безопасности.

**Предупреждение**, неправильное использование некоторых из этих дополнительных опций может привести к потере ваших биткоинов или уничтожению аппаратного кошелька. Поэтому я настоятельно рекомендую вам внимательно прочитать советы и объяснения по каждой опции.

Прежде чем начать, убедитесь, что у вас есть доступ к физической резервной копии вашей мнемонической фразы из 12 или 24 слов, и проверьте ее действительность через следующее меню: `Дополнительно/Инструменты > Опасная зона > Функции семян > Просмотр слов семян`.

![CCQ](assets/fr/01.webp)

## Кодовая фраза BIP39

Если вы не знаете, что такое парольная фраза BIP39, или если вам не совсем понятно, как она работает, я настоятельно рекомендую вам предварительно ознакомиться с этим учебником, в котором изложены теоретические основы, необходимые для понимания рисков, связанных с использованием парольной фразы:

https://planb.network/tutorials/wallet/backup/passphrase-a26a0220-806c-44b4-af14-bafdeb1adce7
Имейте в виду, что после ввода парольной фразы в кошелек одной мнемоники будет недостаточно, чтобы восстановить доступ к биткоинам. Вам понадобятся и мнемоника, и парольная фраза. Более того, вам нужно будет вводить кодовую фразу каждый раз, когда вы разблокируете COLDCARD Q. Это повышает безопасность, делая физический доступ к COLDCARD и знание PIN-кода недостаточными без кодовой фразы.

На картах COLDCARD у вас есть два варианта управления парольной фразой:

1. **Классический ввод:** Вы вводите кодовую фразу вручную при каждом использовании аппаратного кошелька, как и в случае с другими аппаратными кошельками. COLDCARD Q упрощает эту задачу благодаря полноценной клавиатуре.

2. **Вы можете зашифровать свою кодовую фразу и хранить ее на карте microSD. В этом случае вам нужно будет вставлять microSD в COLDCARD Q каждый раз, когда вы его используете. Обратите внимание, что эта карта microSD будет работать только на вашем COLDCARD Q и не является резервной. Поэтому очень важно, чтобы вы также хранили копию вашей ключевой фразы на физическом носителе, например, на бумаге или металле.

Чтобы задать парольную фразу для BIP39, откройте меню "*Парольная фраза*".

![CCQ](assets/fr/02.webp)

Введите парольную фразу с помощью клавиатуры. Обязательно выберите надежную парольную фразу (длинную и случайную) и сделайте физическую резервную копию.

![CCQ](assets/fr/03.webp)

После ввода парольной фразы COLDCARD Q покажет вам отпечаток мастер-ключа нового кошелька, связанного с этой парольной фразой. Обязательно сохраните этот отпечаток. При повторном вводе парольной фразы при использовании устройства в будущем вы сможете проверить, совпадает ли отображаемый отпечаток с сохраненным. Эта проверка гарантирует, что вы не ошиблись при вводе парольной фразы.

![CCQ](assets/fr/04.webp)

Теперь вы можете нажать "*ENTER*", чтобы применить эту парольную фразу к вашей мнемонической фразе и активировать новый кошелек. Если вы предпочитаете сохранить эту кодовую фразу на microSD, вставьте карту в соответствующий слот и нажмите "*1*".

![CCQ](assets/fr/05.webp)

Теперь ваша парольная фраза применена. Отпечаток ключа появится на главном экране и в верхней части экрана.

![CCQ](assets/fr/06.webp)

Каждый раз, когда вы разблокируете COLDCARD Q, вам нужно будет зайти в меню "*Passphrase*" и ввести свою парольную фразу таким же образом, как описано выше, чтобы применить ее к мнемонике, хранящейся в устройстве, и получить доступ к нужному кошельку Bitcoin.

![CCQ](assets/fr/07.webp)

Если вы сохранили парольную фразу на карте памяти microSD, при каждом использовании вставляйте ее в COLDCARD и открывайте меню "*Passphrase*". COLDCARD загрузит кодовую фразу прямо с microSD, поэтому вам не придется вводить ее вручную. Нажмите на кнопку "*Восстановить сохраненное*".

![CCQ](assets/fr/08.webp)

Проверьте правильность длины и первой буквы загруженной парольной фразы.

![CCQ](assets/fr/09.webp)

Убедитесь, что отображаемый отпечаток пальца совпадает с отпечатком вашего кошелька, и нажмите "*Восстановить*".

![CCQ](assets/fr/10.webp)

Помните, что использование парольной фразы означает, что вам нужно будет импортировать новый набор ключей, полученных из комбинации вашей мнемонической фразы и парольной фразы, в программное обеспечение для управления кошельками (например, Sparrow Wallet). Для этого выполните шаг "*Настроить новый кошелек в Sparrow*" в этом другом руководстве:

https://planb.network/tutorials/wallet/hardware/coldcard-q-73e86d1a-6fe6-4d8b-bb15-8690298020e3
## Варианты разблокировки

COLDCARD также имеют множество возможностей для разблокировки устройства. Давайте узнаем больше об этих дополнительных возможностях.

### Хитроумные PIN-коды

Trick PIN - это дополнительный PIN-код, отличный от того, который был задан при первоначальной настройке устройства. Этот код используется для запуска определенных предварительно настроенных действий, как только он вводится при включении COLDCARD. Вы можете настроить несколько Trick PIN-кодов, каждый из которых связан с определенным действием. Эти функции позволяют адаптировать COLDCARD к вашей личной стратегии безопасности. Они особенно полезны в случаях физического давления, например, во время ограбления (в биткойн-сообществе это называют "атакой *5-долларовым ключом*").

Чтобы активировать Trick PIN и связать его с действием, откройте меню `Настройки > Настройки входа в систему > Trick PINs`.

![CCQ](assets/fr/11.webp)

Выберите "*Добавить новый трюк*".

![CCQ](assets/fr/12.webp)

Установите PIN-код, который будет ассоциироваться с действием, и не забудьте сохранить его.

![CCQ](assets/fr/13.webp)

Затем выберите действие, которое будет выполняться автоматически при каждом вводе этого ПИН-кода. Вот список действий, доступных для PIN-кода:


- "*Кирпич Селфи*": Это действие уничтожает оба чипа COLDCARD Q, если введен Trick PIN, делая устройство полностью непригодным для использования. После этого его невозможно будет перепродать, использовать повторно или даже вернуть в Coinkite. Устройство безвозвратно устареет. Эту функцию можно использовать в случае ограбления, чтобы убедить нападающего, что он никогда не сможет получить доступ к вашим биткоинам. **Обратите внимание**: без физического резервного копирования вашей мнемонической фразы и любой парольной фразы ваши биткоины будут безвозвратно потеряны.

![CCQ](assets/fr/14.webp)


- "*Wipe Seed*": Это меню предлагает несколько действий для удаления семени, т.е. сброса COLDCARD без ее уничтожения. В отличие от опции "*Brick Self*", здесь можно будет перенастроить устройство, используя резервную копию вашей мнемонической фразы. Однако без этой резервной копии ваши биткоины будут потеряны. Вот доступные варианты:
 - "*Стереть и перезагрузить*" : Удаляет семена и перезагружает COLDCARD, не выводя на экран никакой информации.
 - "*Сильное стирание*": Бесшумно стирает семя и разблокирует COLDCARD на случайном фальшивом кошельке, как будто ничего не произошло.
 - "*Стереть -> Кошелек*": Незаметно удаляет семя и разблокирует COLDCARD на предварительно настроенном вторичном кошельке, предназначенном в качестве приманки. Этот кошелек может содержать небольшую часть ваших биткоин-сбережений, чтобы удовлетворить злоумышленника.
 - "*Семя стерто, стоп*": Удаляет семя и выводит на экран сообщение `Семя стерто, стоп`.

![CCQ](assets/fr/15.webp)


- "*Кошелек на случай стресса*": С помощью этого действия PIN-код Trick разблокирует кошелек, полученный из семени с помощью BIP85. Этот вторичный кошелек можно использовать в качестве приманки для злоумышленников. COLDCARD действует так, как будто это настоящий кошелек, но без главного PIN-кода (отличного от Trick PIN-кода) злоумышленник никогда не сможет получить доступ к настоящему кошельку. Эта стратегия разработана для того, чтобы заставить людей поверить, что кошелек, привязанный к Trick PIN, является единственным существующим.

![CCQ](assets/fr/16.webp)


- "*Отсчет входа*": В этом меню сгруппированы действия с обратным отсчетом времени до их выполнения. **Предупреждение**, некоторые из них могут уничтожить ваше устройство или привести к потере ваших биткоинов. Вот доступные подпункты:
 - "*Стереть и обратный отсчет* : Очищает семя из памяти COLDCARD, а затем запускает часовой обратный отсчет. Без сохранения мнемоники или парольной фразы ваши биткоины будут потеряны. Эта опция предназначена для того, чтобы обмануть злоумышленника и заставить его думать, что устройство разблокируется по окончании обратного отсчета, в то время как на самом деле оно будет сброшено к заводским настройкам.
 - "*Отсчет и кирпич*": Запускает часовой обратный отсчет, по окончании которого COLDCARD уничтожает два своих защищенных чипа, делая его окончательно непригодным для использования. Без резервного копирования ваши биткоины будут потеряны. Это действие призвано обмануть злоумышленника, который думает, что ждет разблокировки, а на самом деле устройство самоуничтожается.
 - "Просто обратный отсчет" : Запускает простой одночасовой обратный отсчет, после чего COLDCARD перезапускается без каких-либо дальнейших действий. Запись не удаляется, и устройство остается неповрежденным. Будьте осторожны и не путайте это действие с опцией "*Login Countdown*", рассматриваемой в следующих разделах, которая добавляет обратный отсчет к основному PIN-коду, предоставляя доступ к реальному кошельку.

![CCQ](assets/fr/17.webp)


- "*Выглядеть пустой*": Это действие заставляет COLDCARD казаться пустой, создавая впечатление, что семя было удалено. На самом деле ничего не происходит, и семя остается нетронутым. Это имитирует неиспользуемую или сброшенную COLDCARD.

![CCQ](assets/fr/18.webp)


- "Просто перезагрузка" : При использовании Trick PIN-кода COLDCARD просто перезагружается. Никаких других действий не производится.

![CCQ](assets/fr/19.webp)


- "Режим дельты": Это сложное действие, предназначенное для опытных пользователей, разработано для противодействия сложным атакам с принуждением, будь то со стороны государства или родственников, обладающих привилегированной информацией. При активации "Дельта-режима" COLDCARD предоставляет доступ к реальному кошельку, позволяя злоумышленнику перейти на него и убедиться, что это именно тот кошелек. Однако подписи транзакций блокируются, что препятствует переводу биткоинов. Кроме того, доступ к мнемонической фразе заблокирован, и любая попытка ее получить приведет к ее удалению. Для повышения надежности Trick PIN-код, используемый в Delta Mode, должен иметь тот же префикс, что и настоящий PIN-код (для отображения тех же антифишинговых слов), но суффикс должен быть другим.

![CCQ](assets/fr/20.webp)

Выбрав действие, подтвердите свой выбор.

![CCQ](assets/fr/21.webp)

В специальном меню можно просмотреть все настроенные Trick PIN-коды.

![CCQ](assets/fr/22.webp)

Выбрав существующий Trick PIN, вы можете проверить связанное с ним действие. Вы также можете скрыть его с помощью команды "*Hide Trick*", сделав его невидимым в меню Trick PIN. Вы можете удалить его, нажав на "*Удалить трюк*", или изменить PIN-код, сохранив связанное с ним действие, с помощью "*Изменить PIN*".

![CCQ](assets/fr/23.webp)

Опция "*Добавить при ошибке*", доступная в меню "*Трюк PIN*", позволяет настроить определенное действие, которое автоматически запускается после определенного количества неправильных попыток ввода основного PIN-кода. Количество допустимых попыток можно задать во время настройки.

### Клавиши скремблирования

Опция Scramble Keys позволяет скремблировать цифры, отображаемые на кнопках клавиатуры при вводе PIN-кода. Эта функция защищает конфиденциальность вашего PIN-кода даже в случае наблюдения со стороны людей или камер.

Чтобы активировать эту опцию, войдите в меню `Настройки > Настройки входа > Клавиши скремблирования`.

![CCQ](assets/fr/24.webp)

Выберите опцию "*Клавиши скремблирования*".

![CCQ](assets/fr/25.webp)

С этого момента, когда вы разблокируете COLDCARD Q, кнопкам клавиатуры будут присваиваться новые номера в случайном порядке каждый раз, когда вы их используете.

![CCQ](assets/fr/26.webp)

### Обратный отсчет времени для входа в систему

Эта опция позволяет установить систематический обратный отсчет времени при каждой попытке разблокировать COLDCARD. Ее можно включить в стратегию безопасности, задерживая доступ к устройству в случае кражи или устанавливая задержку перед подписанием транзакции, например, чтобы защитить себя в случае задержания. Однако этот обратный отсчет действует во всех случаях, в том числе и при законном использовании COLDCARD, что также обязывает вас проявить терпение. Не путайте эту опцию с действием "*Простой отсчет*", которое активируется только при использовании определенного Trick PIN-кода.

Чтобы настроить эту опцию, откройте меню `Настройки > Настройки входа > Отсчет времени входа`.

![CCQ](assets/fr/27.webp)

Выберите время обратного отсчета. Например, если выбрать 1 час, то при каждой попытке разблокировать COLDCARD Q придется ждать 1 час.

![CCQ](assets/fr/28.webp)

При каждой разблокировке вам будет предложено ввести PIN-код.

![CCQ](assets/fr/29.webp)

Затем дождитесь времени, установленного обратным отсчетом.

![CCQ](assets/fr/30.webp)

По окончании обратного отсчета вам нужно будет снова ввести PIN-код, чтобы получить доступ к устройству.

![CCQ](assets/fr/31.webp)

### Вход в калькулятор

Эта опция позволяет замаскировать вашу COLDCARD под калькулятор при разблокировке. Чтобы активировать эту функцию, войдите в меню `Настройки > Настройки входа > Вход в систему с калькулятором`.

![CCQ](assets/fr/32.webp)

Активируйте опцию, выбрав ее.

![CCQ](assets/fr/33.webp)

С этого момента при каждом включении устройства на экране будет отображаться рабочий калькулятор с основными командами.

![CCQ](assets/fr/34.webp)

Например, вы можете вычислить хэш SHA256 для "*Сеть плана B*".

![CCQ](assets/fr/35.webp)

Чтобы разблокировать COLDCARD в режиме калькулятора, введите префикс вашего PIN-кода, за которым следует тире. Например, если ваш PIN-код - `00-00` (этот код слабый и является лишь примером, поэтому выберите надежный PIN-код), введите `00-`. После этого COLDCARD отобразит два ваших антифишинговых слова.

![CCQ](assets/fr/36.webp)

Затем введите полный PIN-код, разделенный пробелом или тире, например: `00 00`.

![CCQ](assets/fr/37.webp)

После этого COLDCARD выйдет из режима калькулятора и разблокируется в обычном режиме.

## Чистое уничтожение COLDCARD

Если вы планируете избавиться от COLDCARD Q, например, потому что теперь используете другой аппаратный кошелек, важно правильно уничтожить устройство. Это гарантирует, что никакая информация, связанная с вашим кошельком, не сможет быть восстановлена третьей стороной.

Существует три уровня уничтожения информации, в зависимости от ваших потребностей. Прежде чем начать, убедитесь, что ваш кошелек импортирован в другой аппаратный кошелек, что у вас есть доступ ко всем вашим средствам и, самое главное, что у вас есть ваша мнемоническая фраза и любая парольная фраза, обе из которых функционируют. Без резервной копии кошелька уничтожение COLDCARD приведет к потере ваших биткоинов.

Первый уровень уничтожения заключается в удалении только семени. Этот вариант удаляет вашу мнемоническую фразу из памяти COLDCARD, оставляя устройство работоспособным. Это идеальный вариант, если вы хотите использовать COLDCARD Q позже. Чтобы удалить семя из памяти, откройте меню `Дополнительные/Инструменты > Опасная зона > Функции семени > Уничтожить семя`.

![CCQ](assets/fr/38.webp)

Второй уровень уничтожения заключается в постоянном отключении двух защищенных чипов COLDCARD с помощью программного обеспечения. Это действие делает устройство полностью непригодным для использования. Вы не сможете перепродать его, использовать повторно или вернуть в Coinkite: оно будет окончательно уничтожено. Чтобы продолжить, выполните действия, описанные в предыдущем разделе относительно PIN-кода "*Brick Me*" PIN-кода, а затем намеренно введите этот PIN-код при разблокировке COLDCARD.

Третий уровень предполагает физическое уничтожение защищенных компонентов COLDCARD Q. Как и прежде, это сделает устройство безвозвратно непригодным для использования. Для этого с помощью дрели проделайте отверстие в двух микросхемах на верхней правой стороне устройства (перевернутого вверх дном), рядом с надписью "*SHOOT HERE*".

**Важные меры предосторожности** :


- Чтобы избежать риска поражения электрическим током, извлеките из устройства батарейки и отключите его от сети перед началом работы.
- Подождите несколько минут после выключения устройства, прежде чем приступать к бурению.
- Наденьте изолированные перчатки и защитные очки, чтобы обеспечить свою безопасность.

![CCQ](assets/fr/39.webp)

После того как микросхемы будут пробиты, не пытайтесь снова подключить COLDCARD Q.

Поздравляем, теперь вы в курсе всех дополнительных возможностей COLDCARD Q!

Если вы нашли этот урок полезным, я буду очень благодарен, если вы оставите свой отзыв о нем ниже. Не стесняйтесь поделиться этим уроком в своих социальных сетях. Большое спасибо!

Я также рекомендую этот другой учебник, в котором мы обсуждаем использование прямого конкурента CCQ, Ledger Flex:

https://planb.network/fr/tutorials/wallet/hardware/ledger-flex-3728773e-74d4-4177-b39f-bd923700c76a