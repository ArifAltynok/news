<template>
    <body>
		
		<header>
            <div class="header-container">
                <a href="/"><img src="public/Logo.png" width="60px" alt="NEWS"></a>
                <nav>
                    <a href="/">Новости</a>
                    <a href="/chat">Поддержка</a>
                    <a href="https://realty.ya.ru/moskva/">Недвижимость</a>
                    <a href="/weather">Погода</a>
                    <a href="https://afisha.yandex.ru/moscow">Афиша</a>
                    <a href="https://eda.yandex.ru/moscow/collections/shops">Магазины</a>
                    <a href="/about">О нас</a>
                    <a href="/email">Почта</a>
                    <a href="/sport">Спорт</a>
                </nav>
                <div class="white-icons">
                    <a href="/user"><img class="icon1" src="public/user.png" alt="user" width="30px" height="30px"></a>
                    <a href="/addpage"><img class="icon1" src="public/add.png" alt="добавить новость" height="28px" width="28px"></a>
                </div>
            </div>
		</header>
		
		<form action="#" method="post" class="full-news-container">
			<div class="info-container">
				<h4>Категория:</h4>
				<select>
					<option value="property">Недвижимость</option>
					<option value="property">Мир</option>
					<option value="property">Туризм</option>
					<option value="property">Наука</option>
				</select>
			</div>
			<input type="text" placeholder="Текст заголовка" class="news-name">
			<div class="image-container">
				<img class="addnewsimg" src="public/addnews.png">
			</div>
			<div class="full-text" contenteditable=true data-text="Основоной текст новости"></div>
			<div class="button-container">
				<button class="cancel">Отмена</button>
				<button class="add-button-addpage">Опубликовать</button>
			</div>
			<div class="sorry">
				Страница всё ещё в разработке поэтому опубликовать свою новость пока не возможно. Приносим свои извинения
			</div>
		</form>
	</body>
</template>

<script>
export default {
    name: 'AddPage'
}
</script>