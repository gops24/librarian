<template>
    <div class="center">
        <v-row>
            <v-col cols="10" sm ="6" offset-sm="3" md="4" offset-md="4" offset="1">
                <v-avatar size="95" tile>
                    <v-img src="@/assets/logo.png"></v-img>
                </v-avatar>    
            <v-text-field
                label="Username"
                v-model="username"
                outlined>
            </v-text-field>
            <v-text-field
                label="Password"
                v-model="Password"
                type=password
                outlined></v-text-field>
            <v-btn block>
                Login
            </v-btn>
                    
    
            </v-col>
        </v-row>

    </div>
</template>


<script>
</script>

<style lang="scss" scoped>
</style>
