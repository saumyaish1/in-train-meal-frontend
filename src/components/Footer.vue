<template>
    <div>
        <footer id="footer">
            <font-awesome-icon icon="fa-brands fa-twitter" />
            <font-awesome-icon icon="fa-brands fa-facebook" />
            <font-awesome-icon icon="fa-brands fa-instagram" />
            <font-awesome-icon icon="fa-solid fa-envelope" />
            <font-awesome-icon icon="fa-solid fa-user-secret" />

            <p>© Copyright 2022-23 💙Ish</p>
        
        </footer>
    </div>
</template>

<script>
export default {
    name: 'AppFooter',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style scoped>
#footer {
    text-align: center;
    padding: 7% 15%;
    color: #b3b0b0;
}

.social-icon {
    margin: 20px 10px;
}
</style>