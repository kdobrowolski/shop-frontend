<template>
    <article class="Product_card">
        <div class="card_container">
            <img class="container_image" src="~/assets/img/product.jpg" />
            <h2 class="container_title">
                Garnitur Gucci Gang
            </h2>
            <p class="container_price">
                499,99$
            </p>
            <p class="container_rate">
                <font-awesome-icon class="rate_star--filled" :icon="['fa', 'star']" />
                <font-awesome-icon class="rate_star--filled" :icon="['fa', 'star']" />
                <font-awesome-icon class="rate_star--filled" :icon="['fa', 'star']" />
                <font-awesome-icon class="rate_star--filled" :icon="['fa', 'star']" />
                <font-awesome-icon class="rate_star--filled" :icon="['fa', 'star']" />
            </p>
        </div>
    </article>
</template>

<script>
export default {
    
}
</script>