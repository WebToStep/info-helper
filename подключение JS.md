# подключение файла JS
<scrypt src="scrypt.js"> // так можно указать перед закрытием body

# через атрибуты так (в head)
<scrypt src="scrypt.js" defer>  //сначало грузит страницу потом js
<scrypt src="scrypt.js" async>  //сначало грузит страницу и JS как js загрузится выполняет его
