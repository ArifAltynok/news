<template>
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
</template>

<script>
export default {
    name: 'NavComp'
}
</script>