<template>
    <header>
        <div class="logo">Vr center</div>
        <nav class="verhh">
            <div class="gl">Главная</div>
            <div class="gl">О нас</div>
            <div class="gl">Наши Контакты</div>
        </nav>
    </header>
</template>
<script>
export default {
  name: 'HeaderCli'
}
</script>
<style>
header {
    display: flex;
    justify-content: space-between;
    background-color: rgba(0, 0, 0, 0.502);
    padding: 30px;
}
.heads {
    cursor: pointer;
    display: flex;
    color: white;
    gap: 25px;
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 150%;
    justify-content: space-between;
}
.verhh {
    display: flex;
    gap: 70px;
}
.logo {
    font-size: 30px;
    cursor: pointer;
    background-color: #2AA5A0;
    background-image: linear-gradient(90deg, #4332a4, #055f65);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    text-transform: uppercase;
    font-weight: 900;
}

.gl {
    color: white;
    padding: 8px 0;
    border-bottom: 1px solid transparent;
    transition: 0.5s;
    cursor: pointer;
}

.gl:hover {
    border-bottom: 1px solid white;
} 

</style>