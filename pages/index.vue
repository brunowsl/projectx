<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card style="margin-top: 10%">
        <v-card-title class="headline"> Welcome to PROJECTX </v-card-title>
        <v-card-text>
          <v-img src="/images/projectx.png" max-height="200px" />
          <v-container style="width: 400px">
            <v-text-field
              id="txf1"
              solo
              dense
              prepend-icon="mdi-account"
              label="login"
            ></v-text-field>
            <v-text-field
              id="txf1"
              solo
              dense
              prepend-icon="mdi-lock"
              label="password"
            ></v-text-field>
            <v-btn color="success" width="100%">Logar</v-btn>
          </v-container>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>
