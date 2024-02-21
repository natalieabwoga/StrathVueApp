<template>
    <div id = 'homepage'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://i.pinimg.com/564x/55/2d/8a/552d8af844a91600a4bf19abbe632962.jpg"
                            cover
                        ></v-carousel-item>

                    </v-carousel>
                    </v-layout>
                    <v-layout>
                    <v-container>
                        <v-row align="center" justify="center">
                            <div class="d-flex align-center flex-column">
                                <div class="text-subtitle-2">𓍢ִ໋🀦</div>

                                <v-card
                                width="400"
                                title="Gallery"
                                subtitle="Capturing Moments: Explore Our School Gallery!"
                                text="Dive into the vibrant tapestry of school life through our captivating gallery, where moments of learning, creativity, and camaraderie come to life in vivid imagery. From spirited events to academic achievements, our gallery is a visual journey that showcases the dynamic and vibrant essence of our school community."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">𓍢ִ໋🀦</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Resources
                                </template>

                                <template v-slot:subtitle>
                                    Empowering Education: Explore Our Resources Hub
                                </template>

                                <template v-slot:text>
                                    Discover a wealth of educational tools and support in our Resources section, designed to enrich the learning experience for both students and educators. From study materials to academic guides, our curated collection aims to foster academic success and provide a robust foundation for lifelong learning.




                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">𓍢ִ໋🀦</div>

                                <v-card width="400">
                              
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
