# Примеры оформления



## Заголовки.
Для задания заголовка и его уровня используется символ #

	# Заголовок 1 уровня.
# Заголовок 1 уровня.

	## Заголовок 2 уровня.
## Заголовок 2 уровня.

	### Заголовок 3 уровня.
### Заголовок 3 уровня.

	#### Заголовок 4 уровня.
#### Заголовок 4 уровня.
----


## Примеры шрифтов.
Для выделения текста с помощью используются символы * или _.
Текст, выделенный курсивом:

	*Пример*  
*Пример*

	_Пример_
_Пример_

Текст, выделенный полужирным шрифтом:

    **Пример**
**Пример**

	__Пример__
__Пример__


Текст, выделенный курсивным полужирным шрифтом:

	***Пример***
***Пример***

	___Пример___
___Пример___

## Надстрочный и подстрочный интервалы в тексте.

Для задания надстрочного и подствочного интервалов в языке Markdown используются HTML теги /<sub></sub> и /<sup></sup>.  
Например:

	SSR(p) = |f - g<sub>p</sub>|<sup>2</sup>

Будет выглядеть так:    

SSR(p) = |f - g<sub>p</sub>|<sup>2</sup>


## Ссылки.
Пример оформления ссылки выглядит следующим образом:
    
	[Ваза](https://ru.wikipedia.org/wiki/%D0%92%D0%B0%D0%B7%D0%B0 "Необязательная подсказка, выводится при наведении курсора мыши")    
В результате на экран выводится следующее:    
[Ваза](https://ru.wikipedia.org/wiki/%D0%92%D0%B0%D0%B7%D0%B0 "Необязательная подсказка, выводится при наведении курсора мыши")  


## Картинки
Для вставки в текст картинок используется соответсвующий HTML код. 

	<p align="left">
	  <img width="200" height="200" src="https://github.com/blademoon/Coursera_Mathematics_for_Machine_Learning_Specialization/blob/main/Course_1_Mathematics_for_Machine_Learning-Linear_Algebra/Week%201/Test_1-1_picture_8.png">
	</p>



## Цитаты.
Для обозначения цитат в языке Markdown используется символ знак «больше» («>»). ***Уровень цитирования не может превышать 15!*** Цитирование можно использовать как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Например:

    >Это пример цитаты,
    >в которой перед каждой строкой
    >ставится угловая скобка.
	
>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.	
	

    >Это пример цитаты,
    в которой угловая скобка
    ставится только перед началом нового параграфа.
	
    >Второй параграф.
	
>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.

>Второй параграф.

Вложение цитаты в цитату выглядит следующим образом:

    > Первый уровень цитирования
    >> Второй уровень цитирования
    >>> Третий уровень цитирования
    >
    >Первый уровень цитирования

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования



## Греческие буквы.
Для вставки в текст [греческих символов](https://ru.wikipedia.org/wiki/%D0%93%D1%80%D0%B5%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D0%B0%D0%BB%D1%84%D0%B0%D0%B2%D0%B8%D1%82)  используются либо обозначения этих символов, либо их код в кодировке UNICODE. Ниже приведена таблица с заглавными и прописными символами греческого алфавита.    

Заглавные греческие буквы:

| Имя кода | Код | Описание | Отображаемый символ |                                                                 
| -- | -- | -- | -- |                                                                                                   
| \&Alpha; | \&#913; | Большая (заглавная) греческая буква "альфа"| Α |                                                                   
| \&Beta; | \&#914; | Большая (заглавная) греческая буква "бета" | Β |                                                                     
| \&Gamma; | \&#915; | Большая (заглавная) греческая буква "гамма" | Γ |                                                                   
| \&Delta; | \&#916; | Большая (заглавная) греческая буква "дельта" | Δ |                                                                   
| \&Epsilon; | \&#917; | Большая (заглавная) греческая буква "эпсилон" | Ε |                                                               
| \&Zeta; | \&#918; | Большая (заглавная) греческая буква "дзета (зита)" | Ζ |                                                                     
| \&Eta; | \&#919; | Большая (заглавная) греческая буква "эта (ита)" | Η |                                                                       
| \&Theta; | \&#920; | Большая (заглавная) греческая буква "тэта (фита)" | Θ |                                                                   
| \&Iota; | \&#921; | Большая (заглавная) греческая буква "йота" | Ι |                                                                     
| \&Kappa; | \&#922; | Большая (заглавная) греческая буква "каппа" | Κ |                                                                   
| \&Lambda; | \&#923; | Большая (заглавная) греческая буква "лямбда (лямда)" | Λ |                                                                 
| \&Mu; | \&#924; | Большая (заглавная) греческая буква "мю (ми)" | Μ |                                                                         
| \&Nu; | \&#925; | Большая (заглавная) греческая буква "ню (ни) | Ν |                                                                         
| \&Xi; | \&#926; | Большая (заглавная) греческая буква "кси" | Ξ |                                                                         
| \&Omicron; | \&#927; | Большая (заглавная) греческая буква "омикрон" | Ο |                                                               
| \&Pi; | \&#928; | Большая (заглавная) греческая буква "пи" | Π |                                                                         
| \&Rho; | \&#929; | Большая (заглавная) греческая буква "ро" | Ρ |                                                                       
| \&Sigma; | \&#931; | Большая (заглавная) греческая буква "сигма" | Σ |                                                                   
| \&Tau; | \&#932; | Большая (заглавная) греческая буква "тау (тав)" | Τ |                                                                       
| \&Upsilon; | \&#933; | Большая (заглавная) греческая буква "ипсилон" | Υ |                                                               
| \&Phi; | \&#934; | Большая (заглавная) греческая буква "фи" | Φ |                                                                       
| \&Chi; | \&#935; | Большая (заглавная) греческая буква "хи" | Χ |                                                                       
| \&Psi; | \&#936; | Большая (заглавная) греческая буква "пси" | Ψ |                                                                       
| \&Omega; | \&#937; | Большая (заглавная) греческая буква "омега" | Ω |

Маленькие греческие буквы:

| Имя кода | Код | Описание | Отображаемый символ |                                                                 
| -- | -- | -- | -- |                                                                                                   
| \&alpha; | \&#945; | Маленькая греческая буква "альфа" | α |                                                                     
| \&beta; | \&#946; | Маленькая греческая буква "бета"| β |                                                                       
| \&gamma; | \&#947; | Маленькая греческая буква "гамма" | γ |                                                                     
| \&delta; | \&#948; | Маленькая греческая буква "дельта" | δ |                                                                     
| \&epsilon; | \&#949; | Маленькая греческая буква "эпсилон" | ε |                                                                 
| \&zeta; | \&#950; | Маленькая греческая буква "дзета (зита)" | ζ |                                   
| \&eta; | \&#951; | Маленькая греческая буква "эта (ита)" | η |                                                                         
| \&theta; | \&#952; | Маленькая греческая буква "тэта (фита)" | θ |                                                                     
| \&iota; | \&#953; | Маленькая греческая буква "йота" | ι |                                                                       
| \&kappa; | \&#954; | Маленькая греческая буква "каппа" | κ |                                                                     
| \&lambda; | \&#955; | Маленькая греческая буква "лямбда (лямда)" | λ |                                                                   
| \&mu; | \&#956; | Маленькая греческая буква "мю (ми)" | μ |                                                                           
| \&nu; | \&#957; | Маленькая греческая буква "ню (ни)" | ν |                                                                           
| \&xi; | \&#958; | Маленькая греческая буква "кси" | ξ |                                                                           
| \&omicron; | \&#959; | Маленькая греческая буква "омикрон" | ο |                                                                 
| \&pi; | \&#960; | Маленькая греческая буква "пи" | π |                                                                           
| \&rho; | \&#961; | Маленькая греческая буква "ро" | ρ |                                                                         
| \&sigma; | \&#963; | Маленькая греческая буква "сигма" | σ |                                                                     
| \&tau; | \&#964; | Маленькая греческая буква "тау (тав)" | τ |                                                                         
| \&upsilon; | \&#965; | Маленькая греческая буква "ипсилон" | υ |                                                                 
| \&phi; | \&#966; | Маленькая греческая буква "фи" | φ |                                                                         
| \&chi; | \&#967; | Маленькая греческая буква "хи" | χ |                                                                         
| \&psi; | \&#968; | Маленькая греческая буква "пси" | ψ |                                                                         
| \&omega; | \&#969; | Маленькая греческая буква "омега" | ω |  





 


