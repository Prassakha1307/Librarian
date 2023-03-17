<template>
    <div class="center">  
        <v-row>
            <v-col cols="10" offset="1" >
                <v-avatar color="primary" size="95" tile>
                    <v-img src="@/assets/logo.png"></v-img>
                </v-avatar>
                <v-text-field label="Username"></v-text-field>
                <v-text-field label="Password" type="password"></v-text-field>
                <v-btn class="base-inverted" block @click="authentication">
                    Login
                </v-btn>
            </v-col>
        </v-row>
    </div>
</template>

<script>
    export default {
      
        
    }
</script>

<style lang="scss" scoped>

</style>


<style lang="scss" scoped>

</style>