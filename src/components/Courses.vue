<template>
    <div id = "alumni">

        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://s3-ap-south-1.amazonaws.com/ricedigitals3bucket/AUPortalContent/2021/05/31112658/Untitled-design-34.png"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://images.pexels.com/photos/8199605/pexels-photo-8199605.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://images.pexels.com/photos/8199605/pexels-photo-8199605.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                            cover
                        ></v-carousel-item>

                    </v-carousel>
                    </v-layout>
                    <v-layout>
                    <v-container>
                        <v-row align="center" justify="center">
                            <div class="d-flex align-center flex-column">

                            </div>
                                <div class="text-subtitle-2">❀</div>

                                <v-card width="600">
                                <v-card-item>
                                    <v-card-title>{{ componentTitle }}</v-card-title>

                                    <v-card-subtitle>Explore Our Academic Offerings: Diverse Courses for Every Aspiring Mind</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    <v-list
                                :items="courses"
                                item-title="coursename"
                                item-value="id"
                                ></v-list>
                                </v-card-text>
                                </v-card>


                                <div class="mt-4 text-subtitle-2">❀</div>

                        </v-row>
                    </v-container>
                </v-layout>
            </v-container>            
        </div>
</template>

<script>
export default {
  // Properties returned from data() become reactive state
  // and will be exposed on `this`.
  data() {
    return {
      courses:[
        {
            id: 1,
            coursename: 'Financial Economics'
        },
        {
            id: 2,
            coursename: 'Psychology'
        },
        {
            id: 3,
            coursename: 'Computer Science'
        },
        {
            id: 4,
            coursename: 'Financial Engineering'
        },
        {
            id: 5,
            coursename: 'Medicine and Surgery'
        },
        {
            id: 6,
            coursename: 'Education'
        },
        {
            id: 7,
            coursename: 'Architecture'
        },
        {
            id: 8,
            coursename: 'Forestry'
        },
        {
            id: 9,
            coursename: 'Law'
        },
        {
            id: 10,
            coursename: 'Hospitality and Tourism '
        }
      ],
      componentTitle: 'Courses at Strath Uni'
    }
  },

  // Methods are functions that mutate state and trigger updates.
  // They can be bound as event handlers in templates.
  methods: {
    increment() {
      this.count++
    }
  },

  // Lifecycle hooks are called at different stages
  // of a component's lifecycle.
  // This function will be called when the component is mounted.
  mounted() {
    console.log(`The initial count is ${this.count}.`)
  }
}
</script>



