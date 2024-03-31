import { VCardItem } from 'vuetify/components';
<template>
  <VCard class="expense mx-auto">
    <VCardTitle class="expense__title text-center">
      <h1 class="font-weight-regular">Expenses</h1>
    </VCardTitle>
    <VCardItem
      class="expense__header d-flex flex-column align-center justify-center"
    >
      <p class="text-center">Spend this month</p>
      <h2 class="text-h2 text-error">$-865.00</h2>
    </VCardItem>
    <VCardItem class="expense__main">
      <VList class="expense__list">
        <VListItem>
          <VRow align="center">
            <VCol cols="2">
              <div class="d-flex justify-center">
                <VIcon
                  class="mx-auto"
                  icon="mdi-facebook"
                  size="large"
                  color="purple"
                ></VIcon>
              </div>
            </VCol>
            <VCol cols="7" sm="8">
              <h3 class="text-h6">Gas</h3>
              <p>02:05 PM</p>
            </VCol>
            <VCol cols="3" sm="2">
              <p
                class="text-error font-weight-regular text-center text-body-1 text-sm-h6"
              >
                -10$
              </p>
            </VCol>
          </VRow>
        </VListItem>
        <VListItem>
          <VRow align="center">
            <VCol cols="2">
              <div class="d-flex justify-center">
                <VIcon
                  class="mx-auto"
                  icon="mdi-facebook"
                  size="large"
                  color="purple"
                ></VIcon>
              </div>
            </VCol>
            <VCol cols="7" sm="8">
              <h3 class="text-h6">Gas</h3>
              <p>02:05 PM</p>
            </VCol>
            <VCol cols="3" sm="2">
              <p
                class="text-error font-weight-regular text-center text-body-1 text-sm-h6"
              >
                -10$
              </p>
            </VCol>
          </VRow>
        </VListItem>
        <VListItem>
          <VRow align="center">
            <VCol cols="2">
              <div class="d-flex justify-center">
                <VIcon
                  class="mx-auto"
                  icon="mdi-facebook"
                  size="large"
                  color="purple"
                ></VIcon>
              </div>
            </VCol>
            <VCol cols="7" sm="8">
              <h3 class="text-h6">Gas</h3>
              <p>02:05 PM</p>
            </VCol>
            <VCol cols="3" sm="2">
              <p
                class="text-error font-weight-regular text-center text-body-1 text-sm-h6"
              >
                -10$
              </p>
            </VCol>
          </VRow>
        </VListItem>
        <VListItem>
          <VRow align="center">
            <VCol cols="2">
              <div class="d-flex justify-center">
                <VIcon
                  class="mx-auto"
                  icon="mdi-facebook"
                  size="large"
                  color="purple"
                ></VIcon>
              </div>
            </VCol>
            <VCol cols="7" sm="8">
              <h3 class="text-h6">Gas</h3>
              <p>02:05 PM</p>
            </VCol>
            <VCol cols="3" sm="2">
              <p
                class="text-error font-weight-regular text-center text-body-1 text-sm-h6"
              >
                -10$
              </p>
            </VCol>
          </VRow>
        </VListItem>
        <VListItem>
          <VRow align="center">
            <VCol cols="2">
              <div class="d-flex justify-center">
                <VIcon
                  class="mx-auto"
                  icon="mdi-facebook"
                  size="large"
                  color="purple"
                ></VIcon>
              </div>
            </VCol>
            <VCol cols="7" sm="8">
              <h3 class="text-h6">Gas</h3>
              <p>02:05 PM</p>
            </VCol>
            <VCol cols="3" sm="2">
              <p
                class="text-error font-weight-regular text-center text-body-1 text-sm-h6"
              >
                -10$
              </p>
            </VCol>
          </VRow>
        </VListItem>
        <VListItem>
          <VRow align="center">
            <VCol cols="2">
              <div class="d-flex justify-center">
                <VIcon
                  class="mx-auto"
                  icon="mdi-facebook"
                  size="large"
                  color="purple"
                ></VIcon>
              </div>
            </VCol>
            <VCol cols="7" sm="8">
              <h3 class="text-h6">Gas</h3>
              <p>02:05 PM</p>
            </VCol>
            <VCol cols="3" sm="2">
              <p
                class="text-error font-weight-regular text-center text-body-1 text-sm-h6"
              >
                -10$
              </p>
            </VCol>
          </VRow>
        </VListItem>
      </VList>
    </VCardItem>
    <VCardItem class="expense__footer">
      <VRow class="text-center" align="center">
        <VCol cols="4">
          <VBtn prepend-icon="mdi-google-analytics">
            Analytics
          </VBtn>
        </VCol>
        <VCol cols="4">
          <VBtn icon="mdi-plus"></VBtn>
        </VCol>
        <VCol cols="4">
          <VBtn prepend-icon="mdi-notification-clear-all">
            Change logs
          </VBtn>
        </VCol>
      </VRow>
    </VCardItem>
  </VCard>
</template>

<style scoped>
.expense {
  height: 100vh;
  max-width: 800px;
  position: relative;
}

.expense__title {
  height: 10%;
}

.expense__header {
  height: 30%;
}

.expense__main {
  height: 52%;
}

.expense__list {
  max-height: 300px;
}

.expense__footer {
  width: 100%;
  height: 8%;
  position: absolute;
  bottom: 0;
}

.expense__footer :deep(.v-card-item__content) {
  overflow:visible
}
</style>
