<template>
    <nav class="Nav" :class="{ 'opened': isActive }">
        <div class="Nav_leftside">
            <font-awesome-icon class="leftside_user" :icon="['far', 'user']" />
            <font-awesome-icon class="leftside_heart" :icon="['far', 'heart']" />
        </div>
        <div class="Nav_logo">
            ShopOnline.
        </div>
        <div class="Nav_rightside">
            <font-awesome-icon class="rightside_search" icon="magnifying-glass" />
            <font-awesome-icon class="rightside_cart" icon="cart-shopping" />
        </div>
        <section class="Nav_menu">
            <ul class="menu_list">
                <li class="list_item">Strona główna</li>
                <li class="list_item">Sklep</li>
                <li class="list_item">Kontakt</li>
                <li class="list_item">FAQ</li>
            </ul>
        </section>
        <font-awesome-icon class="Nav_open_icon" icon="bars" @click="toggleNav" />
        <font-awesome-icon class="Nav_close_icon" icon="xmark" @click="toggleNav" />
    </nav>
</template>

<script>
export default {
    data: () => ({
        isActive: false,
    }),
    methods: {
        toggleNav() {
            this.isActive = !this.isActive;
        }
    }
}
</script>