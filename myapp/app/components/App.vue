<template>
  <Page>
    <ActionBar title="My App">
      <NavigationButton text="Go back"  />
    </ActionBar>
    <!-- <GridLayout colums="*" rows="*">
      <Label class="message" :text="msg" col="0" row="0"/>
    </GridLayout> -->
    <!-- <AbsoluteLayout backgroundColor="#3c495e">
      <Label text="10,10" left="10" top="10" width="100" height="100" backgroundColor="#43b883"/>
      <Label text="120,10" left="120" top="10" width="100" height="100" backgroundColor="#43b883"/>
      <Label text="10,120" left="10" top="120" width="100" height="100" backgroundColor="#43b883"/>
      <Label text="120,120" left="120" top="120" width="100" height="100" backgroundColor="#43b883"/>
      <Label text="30,40" left="30" top="40" width="100" height="100" backgroundColor="#43b883"/>
    </AbsoluteLayout> -->
    <!-- <DockLayout stretchLastChild="true" backgroundColor="#3c495e" color="#fff">
      <Label text="left" dock="left" width="40" backgroundColor="#43b883"/>
      <Label text="top" dock="left" width="40" backgroundColor="#289062"/>
      <Label text="right" dock="left" width="40" backgroundColor="#43b883"/>
      <Label text="bottom" dock="left" width="40" backgroundColor="#289062"/>
      <Label text="center" backgroundColor="#1c6b48" />
    </DockLayout> -->
  <FlexboxLayout color="#fff">
    <!-- <Label text="first" width="33.335%" backgroundColor="#43b883"/>
    <Label text="second" width="33.33%" backgroundColor="#1c6b48"/> -->
    <Label text="third" width="33.335%" backgroundColor="#289062"/>
  </FlexboxLayout>
  </Page>
</template>

<script>
export default {
  data() {
    return {
      msg: "Hello World!"
    };
  }
};
</script>

<style scoped>
ActionBar {
  background-color: #53ba82;
  color: #ffffff;
}

.message {
  vertical-align: center;
  text-align: center;
  font-size: 20;
  color: #333333;
}
</style>
