<template>
  <div id="detail">
    <div id="page-actions">
      <div id="dashboards-container"></div>
      <div id="panel-with-buttons-icons"></div>
    </div>
    <div id="dataset-viewer">
      <div id="advanced-dim-filter"></div>
      <div id="switch-gadget"></div>
      <div id="visualization"></div>
    </div>
  </div>
</template>

<style>
  body {
    background: #efefef;
  }

  #page-actions {
    margin-top: 50px;
    height: 50px;
    background: #F5F5F5;
  }

  
  #dashboards-container {
    float: left;
    width: 340px;
    height: 100%;
    background: #bddfb6;
  }

  #panel-with-buttons-icons {
    float: right;
    width: 430px;
    height: 100%;
    background: #e162bc61;
  }

  #dataset-viewer {
    /* margin-top: 50px; */
    width: 100%;
    height: 750px;
    background: #db1a5c21;
  }

  #advanced-dim-filter {
    float: left;
    width: 260px;
    height: 100%;
    background: red;
  }

  #switch-gadget {
    float: left;
    width: 90px;
    height: 100%;
    background-color: blue;
  }

  #visualization {
    float: left;
    width: 1200px;
    height: 100%;
    background: green;
  }
</style>