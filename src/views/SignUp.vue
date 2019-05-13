<template>
    <div class="signUp">
    
         <v-layout>
        <v-flex>
        <v-card dark max-width="600px">
            <v-card>
                <v-card-title>
                    <h1>Create User</h1>
                </v-card-title>
                <v-card-text>
                    <v-form class="px-3">
                        <v-text-field label="Enter Email" v-model="email" prepend-icon="email"></v-text-field>
                    </v-form>
                    <p><a href="/signin">Already have an Account?</a></p>                    
                    <br/>
                    <v-btn color="primary">Next</v-btn>
                </v-card-text>
            </v-card>
        </v-card>
        </v-flex>
         </v-layout>
        



         <v-layout align-center justify-center>
        <v-flex>
         <v-card dark id="two" max-width="600px">
            <v-card>
                <v-card-title>
                    <h1>Enter Password</h1>
                </v-card-title>
                <v-card-text>
                    <v-form class="px-3">
                        <p>Enter the password you would like to use with your account.</p>
                        <v-text-field label="Password" v-model="password" prepend-icon="fingerprint"></v-text-field>
                    </v-form>              
                    <v-btn color="primary">Back</v-btn>
                    <v-btn float="right" color="primary">Next</v-btn>
                </v-card-text>
            </v-card>
        </v-card>
        </v-flex>
         </v-layout>
        


  </div>
</template>

<script>
export default {
    data(){
        return{
            el:0
        }
    }
}
</script>

<style>

</style>

