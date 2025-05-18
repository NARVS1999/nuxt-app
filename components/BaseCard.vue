<template>
    <v-app>
        <v-container>
            <v-row>
                <v-col cols="12" sm="6" md="4" lg="3" v-for="n in 20" :key="n">
                    <v-card
                        :title="'Card title ' + n"
                        :subtitle="'Subtitle ' + n"
                        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam in dui mauris."
                        variant="outlined"
                        rounded="lg"
                        color=""
                        elevation="2"
                    >
                        <v-card-actions>
                            <v-btn color="primary" variant="elevated">Button {{ n }}</v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>
    </v-app>
</template>
