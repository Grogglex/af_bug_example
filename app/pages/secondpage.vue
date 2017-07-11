<template>
  <f7-page>
    <f7-navbar :title="$root.config.title" />
    <f7-block >Second Page </f7-block>
    <f7-block> <f7-link href="thirdpage" text="Third Page"> </f7-link></f7-block>
    <f7-block> <f7-link href="home" text="Home"> </f7-link></f7-block>
  <f7-toolbar tabbar bottom>
    <f7-link icon="icon-1" text="Tab 1" tab-link="#tab1"></f7-link>
    <f7-link icon="icon-2" text="Tab 2" tab-link="#tab2"></f7-link>
  </f7-toolbar>
  <f7-tabs>
    <f7-tab id="tab1" active>Tab 1 content...</f7-tab>
    <f7-tab id="tab2">Tab 2 content...</f7-tab>
  </f7-tabs>
</f7-page>
</template>
