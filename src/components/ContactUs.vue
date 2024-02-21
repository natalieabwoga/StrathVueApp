<<template>
    <div id = 'contactus'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://as2.ftcdn.net/v2/jpg/00/76/06/53/1000_F_76065302_DFWHrbVmQMdaZJVcsMHtFWe6TEcN0zE3.jpg"
                            cover
                        ></v-carousel-item>

                    </v-carousel>
                    </v-layout>
                    <v-layout>
                    <v-container>
                        <v-row align="center" justify="center">
                            <div class="d-flex align-center flex-column">
                                <div class="text-subtitle-2">☏</div>

                                <v-card
                                width="400"
                                title="Contact Us"
                                subtitle="Phone Number"
                                text="+254707604563"
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">☏</div>

                                <v-card width="400">
                                

                                <template v-slot:subtitle>
                                    Email address
                                </template>

                                <template v-slot:text>
                                    strathmoreuniversity@gmail.com




                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">☏</div>

                                <v-card width="400">
                                <v-card-item>

                                    <v-card-subtitle>Physical address</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Ole Sangale Road, Madaraka.





                                </v-card-text>
                                </v-card>
                            </div>
                        </v-row>
                    </v-container>
                </v-layout>
            </v-container>
    </div>
</template>
<script setup>
  const variants = ['elevated', 'flat', 'tonal', 'outlined']
</script>