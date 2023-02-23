
# How to use

1.  Создаем структуру проекта 
	1. index.html
		1. `touch index.html`
		2. `!` делаем стандарную страницу
	2. Папки 
		1. `mkdir pages blocks fonts vendor scripts images`
			1. pages
			2. blocks
			3. fonts
			4. vendor
			5. scripts
			6. images
2. Добавляем фаил главных стилей
	1. Созадем фаил входную точку стилей `touch pages/index.css`
	2. Добавляем ссылку в главный html `<link rel="stylesheet" href="./pages/index.css">`
3. Добавляем нормализационные стили или полностью обнуляющие
	1. Можно скачать https://necolas.github.io/normalize.css/
	2. Помещаем в [[normolize.css]] в папку vendor
	3. [[Добавить ссылку на file.css в index.css]]
4. Добавляем шрифты
	1. [[Создаем фаил css для шрифтов]] `touch fonts/google_fonts.css`
	2. [[Добавить ссылку на file.css в index.css]]
5. Добавляем базовую разметку в главный html
	1. `<body class="root">`
	2. Добавляем стили к классу `root` и подключаем их к главному `index.css`
		2. `mkdir blocks/root`
		3. `touch blocks/root/root.css` [[Код в root.css]]
		4. `pages/index.css` [[Добавить ссылку на file.css в index.css]]
	3. Добавляем общий контейнер для всей страницы
		1.  `....<body class="root"><div class="page"></div></body>...` 
		2. Добавляем blocks/page/[[page.css]]
		3. [[Добавить ссылку на file.css в index.css]]
	4. Добавляем контейнер для header
		1. `<div class="page"><header class="header"></header></div>`
		2. Добавляем blocks/header/[[header.css]]
		3. [[Добавить ссылку на file.css в index.css]]
	5. Добавляем контейнер для main
		1. `<main class="content">content</main>`
		2. Добавляем blocks/content/[[content.css]]
		3. [[Добавить ссылку на file.css в index.css]]
	6. Добавляем контйнер для footer
		1. `<footer class="footer ">footer</footer>`
		2. Добавляем blocks/footer/[[footer.css]]
		3. [[Добавить ссылку на file.css в index.css]]
6. Подключаем JavaScript 
	1. `touch scripts/index.js`
	2.  В index.html `<body> ... <script src="./scripts/index.js" defer></script></body>`




## Links
[[VanilaJS]]
