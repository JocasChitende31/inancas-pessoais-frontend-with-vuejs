<template>
    <div class="corrency-amount">
        <div class="corrency">
            <div class="title">
                <h3>AOA-KWZ</h3>
            </div>
        </div>
        <div class="line-devisor">
            <h3></h3>
        </div>
        <div>
            <div class="amount">
                <div class="title">
                    <img src="https://cdn-icons-png.flaticon.com/256/4481/4481185.png" alt="">
                    <!-- <h3>300.000,00</h3> -->
                </div>
            </div>
        </div>
    </div>
    <div class="title-AOA">
        <h3>AOA-KWZ</h3>
    </div>
    <div class="description">
        <h5>A sua gestão pessoal você faz aqui - <b>&copysr;weTenGrow</b>, <span>melhoramos para juntos crescer.</span>
        </h5>
    </div>
</template>
<script setup>

</script>

<style>
.title-AOA {
    display: flex;
    position: absolute;

    top: 155px;
    left: 28px;
    /* bottom: 200px; */
    margin-left: 5px;
    z-index: 1;

    h3 {
        /* color: hsl(33, 87%, 50%); */
        color: hsl(33, 87%, 50%);
        font-weight: bold;
        letter-spacing: .05px;
        font-size: 2rem;
        opacity: .8;

    }
}

.description {
    position: absolute;
    top: 196px;
    left: 32px;
    /* left: 188.5px; */

    h5 {
        color: black;
        font-weight: 500;
        opacity: .8;
        letter-spacing: .5px;
        font-size: 1.2rem;

        b {
            font-weight: 500;
            color: #162249;
            opacity: .8;
        }
    }
}
</style>
