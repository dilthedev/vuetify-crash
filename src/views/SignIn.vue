<template>
   <div class="signIn">
        
        <div class="one">
    <v-layout>
    <v-flex offset-md4>
        <v-card dark max-width="600px">
            <v-card>
                <v-flex>
                <v-card-title>
                    <h1>Sign In</h1>
                </v-card-title>
                <v-card-text>
                    <v-form class="px-3">
                        <v-text-field label="Email or Username" v-model="email" prepend-icon="email"></v-text-field>
                    </v-form>
                    <p>No Account? <a href="/signup">Create One</a></p>
                    <a href="">Sign In Options</a>
                    <br/>
                    <v-btn right color="primary" @click="step = 1">Next</v-btn>
                </v-card-text>
                </v-flex>
            </v-card>            
        </v-card>
        </v-flex>
        </v-layout>

        </div>
        
        
        <div class="two">
    <v-layout>
    <v-flex offset-md4>
         <v-card dark max-width="600px">
            <v-card>
                <v-card-title>
                    <h1>Enter Password</h1>
                </v-card-title>
                <v-card-text>
                    <v-form class="px-3">
                        <v-text-field label="Password" v-model="password" prepend-icon="fingerprint"></v-text-field>
                    </v-form>
                    <v-checkbox v-model="checkbox1" label="Keep Me signed In"></v-checkbox>
                    <p><a href="#">Forgot my password?</a></p>                  
                    <v-btn color="primary">Back</v-btn>
                    <v-btn float color="primary">Next</v-btn>
                </v-card-text>
            </v-card>
        </v-card>
                                            <!-- <v-layout>
                                                <v-flex offset-sm3>                                            
                                                <v-card>
                                                <v-card-text >
                                                    <v-text-field label="Email"></v-text-field>
                                                    <v-text-field label="Password"></v-text-field>
                                                </v-card-text>
                                                <v-card-actions>
                                                    <v-layout row>
                                                    <v-flex>
                                                        <v-btn  primary>
                                                        Signup
                                                        </v-btn>
                                                    </v-flex>
                                                    </v-layout>
                                                </v-card-actions>
                                            </v-card>
                                            </v-flex>
                                            </v-layout> -->

        </v-flex>
        </v-layout>

        </div>

  </div>

</template>

<script>
export default {
    name:'signIn',
    data(){
        return{
            e1:0
        }
    }
}
</script>

<style scoped>

</style>

