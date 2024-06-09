<template>
    <div>
        <section class="project_center">
            <div class="project__count-page">
                <div class="project__count-page-wrap">
                    <router-link to="/home" class="project__count-page-number router-link">01</router-link>
                        <router-link to="/project" class="project__count-page-number router-link">02</router-link>
                        <router-link to="/blog" class="project__count-page-number router-link">03</router-link>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'ProjectComponentPagination',

    data() {
        return {
        }
    },
}


</script>
<style scoped>
.project_center {
    margin-top: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;

}

.project_count-page {
    margin-top: 51px;
    margin-bottom: 200px;
    display: flex;
    justify-content: center;
}

.project__count-page-wrap {
    display: flex;
    gap: 20px;
}

.project__count-page-number {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: nowrap;
    border: 1px #cda274 solid;
    width: 52px;
    height: 52px;
    border-radius: 52px;
}

.project__count-page-number-text {
    color: #292f36;
    font-size: 16px;
    font-style: normal;
    line-height: 150%;
    text-transform: capitalize;
}

.hover {
    background: #f4f0ec;
    border: none;
    width: 54px;
    height: 54px;
}

.project__count-page-svg {
    fill: #f4f0ec;
}
</style>