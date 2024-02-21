<template>
    <div id = 'aboutus'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://www.brookings.edu/wp-content/uploads/2017/01/college_graduates010.jpg"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://edsource.org/wp-content/uploads/2023/02/DCTrip2-1024x771.jpg"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://img.freepik.com/free-photo/study-group-african-people_23-2149156424.jpg?t=st=1708421844~exp=1708422444~hmac=3bb4031890734febb2226de917f2a7a09437f49e3b6e654b3f624d636a49db0c"
                            cover
                        ></v-carousel-item>
                    </v-carousel>
                    </v-layout>
                    <v-layout>
                    <v-container>
                        <v-row align="center" justify="center">
                            <div class="d-flex align-center flex-column">
                                <div class="text-subtitle-2">𖤐</div>

                                <v-card
                                width="400"
                                title="Mission and Vision"
                                subtitle="Guiding Principles: Our Mission and Vision"
                                text="Embarking on a journey of academic excellence and holistic development, Strathmore University is driven by a steadfast mission and vision. Our mission is to empower students with a dynamic and inclusive learning environment that fosters intellectual curiosity, critical thinking, and a lifelong love for learning. At the core of our vision is the commitment to nurturing well-rounded individuals equipped with the skills, values, and resilience needed to thrive in an ever-evolving world. We aspire to cultivate a community where diversity is celebrated, creativity is nurtured, and each student is inspired to reach their full potential. With a dedication to excellence, Strathmore University is shaping future leaders who will contribute positively to society and make a lasting impact. Welcome to a learning environment where aspirations take flight, and every student is encouraged to soar to new heights."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">𖤐</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    History and Heritage
                                </template>

                                <template v-slot:subtitle>
                                    Proud Legacy: Tracing Our History and Heritage
                                </template>

                                <template v-slot:text>
                                    Delving into the roots of excellence, Strathmore University's history and heritage stand as pillars of its distinguished legacy. Established in 1961 as an Institute of Accountancy, the institution has evolved into a leading private university in East Africa. Over the decades, Strathmore has been committed to providing high-quality education, rooted in ethical values and a spirit of service. Our heritage encompasses a rich tapestry of academic achievements, influential alumni, and a commitment to societal impact. From humble beginnings, Strathmore University has grown into an esteemed center of learning, recognized for its innovative programs, global outlook, and unwavering dedication to shaping leaders with a profound sense of responsibility. Explore our journey through time, where tradition meets modernity, and discover the enduring legacy that continues to inspire generations of Strathmore students.





                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">𖤐</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Leadership and Faculty</v-card-title>

                                    <v-card-subtitle>Meet Our Inspiring Leaders and Dedicated Faculty</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Welcome to the Heart of Strathmore: Our Esteemed Leadership and Faculty. At Strathmore University, our commitment to academic excellence is driven by the exceptional leadership and dedicated faculty members who shape the educational landscape within our institution. Led by visionary leaders, our university fosters an environment where innovation, integrity, and transformative learning thrive. Our accomplished faculty members, renowned in their respective fields, bring a wealth of knowledge and experience to the classrooms, ensuring our students receive a world-class education. Together, our leaders and faculty create a dynamic and nurturing community that empowers students to achieve their academic and personal aspirations. Explore the profiles of these inspiring individuals who play a pivotal role in shaping the future leaders at Strathmore University.





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
