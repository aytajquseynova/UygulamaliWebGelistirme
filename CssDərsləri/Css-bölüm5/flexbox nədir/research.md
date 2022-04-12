### justify-content üfüqi vəziyyətdə

- flex-start: Elementləri flexbox container'ın sol tərəfinə düzür.
- flex-end: Elementləri flexbox container'ın sağ tərəfinə düzür.
- center: Elementləri flexbox container'ın orta tərəfinə düzür.
- space-between: Elementlər bərabər aralıqlarla üfüqi yayılır.
- space-around: Elementlər ətraflarında bərabər aralıqlar olacaq şəkildə üfüqi yayılır

### align-items şaquli vəziyyətdə

- flex-start: Elementləri flexbox container'ın yuxarısına düzür.
- flex-end: Elementləri flexbox container'ın aşağısına düzür.
- center: Elementləri flexbox container'ın şaquli ortasına düzür.
- baseline: Elementləri flexbox container'ə üfüqi(baseline) düzür.
- stretch: Elementləri flexbox container boyunca uzanırlar

### flex-direction elementlərin istiqamətini təyin edir

- row: Elementlər yazı istiqaməti ilə eyni istiqamətdə olur.
- row-reverse: Elementlər yazı istiqaməti ilə əks istiqamətdə olur.
- column: Elementlər yuxarıdan aşağıya düzülür.
- dcolumn-reverse: Elementlər aşağıdan yuxarıya düzülür.

### Elementlərin başlanğıc dəyəri 0`dır, amma biz bu dəyəri pozitiv və ya neqativ olaraq bərabərləşdirə bilərik.

### Elementlərə tətbiq edə biləcəyimiz bir başqa qayda align-self`dir. align-items qaydası ilə eyni dəyərləri alır və bu dəyəri o element üçün tətbiq edir.

###

Tutaq ki, flexfroggy oyununda bütün qurbağalar tək sıra nilufər yarpağına sıxışınlar. flex-wrap qaydasını işlədərək biz problemi aradan qaldıra bilərik

- nowrap: Bütün elementlər tək sətirə sığır.
- wrap: Elementlər sətirlərə bölünür.
- wrap-reverse: Elementlər sətirlərə tərs istiqamətdə düzülür.

### flex-direction ve flex-wrap qaydaları, flex-flow qısa yazı qaydası ilə yazıla bilərlər. Bu qısa yazılma tərzi iki dəyər arasında boşluq buraxılmaqla yazılır.

Məsələn , flex-flow: row wrap qaydası ilə row və wrap dəyərlərini eyni anda vermək mümkündür.

### align-content qaydası ilə sətirləri bir-birindən ayıra bilərsiniz

- flex-start:Sətirlər flex-container-in təpəsində toplanır.
- flex-end:Sətirlər flex-container-in aşağısında toplanır.
- center: Sətırlər flex container'ın şaquli ortasında toplanır.
- space-between: Sətirlər aralarında eyni qədər boşluq qalacaq şəkildə yayılırlar.
- space-around: Sətirlər etraflarında eyni qədər boşluk kalacak şəkildə yayılırlar.
- stretch: Sətirlər flex container'ı tutmaq üçün uzanır
- Bu sizi çaşdıra bilər, amma align-content sətirlər üçün aralıqları müəyyən edərkən, align-items item`lərin flex container içində necə bərabər düzüləcəyini təyin edir. Tək sətir olduqda align-content qaydasının heç bir təsiri olmur.
