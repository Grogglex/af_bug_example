<template>
  <f7-page>
    <f7-navbar :title="$root.config.title" />
    <f7-block inner inset>It works!</f7-block>
    <f7-block>
      <f7-button big fill raised bg="green" href="https://github.com/scriptPilot/app-framework/blob/master/DOCUMENTATION.md" external>Documentation</f7-button>
      <f7-link href="secondpage" text="Second Page"></f7-link>
    </f7-block>
  </f7-page>
</template>
