# goit-markup-hw-03

2. Нормализуем CSS с помощью подключение modern-normalize.min.css. Подключаем ссылкой в head перед подключением css файла. 
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css">





3. Последовательность подключения:
1. Шрифты
2. Нормалайз
3. CSS


a {
    color:currentColor; (применить цвет родителей)
}
text-align: center; (выравнивает текст по центру)


.container {
	width: 100%;
	max-width: 1200px;
	margin-left: auto;
	margin-right: auto;
	padding-left: 15px;
	padding-right: 15px;
	outline: 3px solid red;
}
.section {
	padding-top: 94px;
	padding-bottom: 94px;
}







<!--   Обязательно задаем это значение документу
    html {
	box-sizing: border-box;
    }
    *,
    *::before,
    *::after {
	box-sizing: inherit;
    } -->