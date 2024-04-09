<template>
    <div class="jumbotron">
        <p>{{ paragraph }}</p>
    </div>
</template>

<script>
export default {
    name: 'Jumbotron',
    data() {
        return {
            paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur error fugit architecto veritatis dignissimos, modi beatae saepe at, eius alias nesciunt placeat cum excepturi vitae? Provident qui ipsa ab dolorem corrupti nostrum, quas tempore suscipit. Veritatis quibusdam accusamus, recusandae, accusantium totam facere nostrum ut necessitatibus unde nam debitis mollitia quaerat iste quo sed, adipisci dolores odio numquam asperiores. Odit iste iure laudantium soluta sapiente amet dolorum dolore totam illum quod facere eaque eveniet doloribus culpa molestias voluptates repellat iusto, ad sunt mollitia. Nesciunt corporis sunt quis, suscipit dolores vitae odit nisi exercitationem laborum veritatis beatae quisquam commodi id pariatur amet',
        }
    }
}
</script>

<style lang="scss" scoped>
p {
    font-size: 1.5rem;
    line-height: 1.5;
    text-align: center;
}

.jumbotron {
    border: 1px solid red;
    background-color: #f5f5f5;
    padding: 2rem;
    border-radius: 0.5rem;
    width: 500px;
    display: flex;
    margin: 0 auto;
}
</style>