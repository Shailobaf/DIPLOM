<template>
    <main>
        <div class="pog">
            <h1 class="viz">Погрузитесь в мир цифровой иллюзии <br></h1>
            <h2 class='viz'> Мы проведём вам экскурсию </h2>
        </div>
    </main>
</template>

<script>
export default {
  name: 'MainCli',
}
</script>

<style>
main {
    display: flex;
    align-items: flex-end;
    justify-content: center;
    height: 64vh;
}
.pog {
    font-size: 21px;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    /* background-image: linear-gradient(90deg, #4736aa50, #0c9da74a); */
}
.viz {
    color: white;
    border-radius: 50px;
}
</style>