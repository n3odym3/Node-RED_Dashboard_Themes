# Node-RED Dashboard Themes
Custom CSS themes for the Node-RED Dashboard

## Theme 1

### Before 
<img src="https://github.com/n3odym3/Node-RED_Dashboard_Themes/blob/main/images/Theme1_Before.png" width="50%">

<img src="https://github.com/n3odym3/Node-RED_Dashboard_Themes/blob/main/images/Theme1_BeforeLeft.png" width="20%">

### After

<img src="https://github.com/n3odym3/Node-RED_Dashboard_Themes/blob/main/images/Theme1_After.png" width="50%">

<img src="https://github.com/n3odym3/Node-RED_Dashboard_Themes/blob/main/images/Theme1_AfterLeft.png" width="20%">

### Flow 

    [{"id":"2cc22929a47b82b3","type":"ui_template","z":"10ac3884.80bbe7","group":"d783cb980c3979fc","name":"Node-Red Dashboard Custom CSS","order":1,"width":0,"height":0,"format":"<style>\n\n    /*Main background*/\n    body {\n        background: -webkit-linear-gradient(\n            55deg,\n            #009785 0%,\n            #245aa5 50%,\n            #b800e9 100%\n            );\n    }\n\n    /*Top bar*/\n    body.nr-dashboard-theme md-toolbar,\n    body.nr-dashboard-theme md-content md-card {\n        background-color: transparent !important;\n        color: #FFFFFF !important;\n    }\n\n\n    /*Left menu*/\n    /*Sidebar*/\n    body.nr-dashboard-theme md-sidenav {\n        color: white !important;\n        background-color: rgba(0,0,0,0) !important;\n    }\n    /*Hover selection*/\n    a.md-no-style, button.md-no-style {\n        border-radius: 10px !important;\n    }\n    /*Selected*/\n    .nr-menu-item-active div button {\n        border-right: 4px solid rgb(41 98 255) !important;\n    }\n    /*List*/\n    body.nr-dashboard-theme md-sidenav div.md-list-item-inner {\n        color: white !important;\n        background-color: rgba(40,85,165,1) !important;\n        border-radius: 10px !important;\n    }\n\n\n    /*Groups*/\n    ui-card-panel {\n        background-color: rgba(255,255,255,0.1) !important;\n        border-radius: 10px !important;\n    }\n    .nr-dashboard-theme ui-card-panel {\n        border: none !important;\n    }\n    /*Name groups*/\n    .nr-dashboard-theme ui-card-panel p.nr-dashboard-cardtitle {\n        color: rgba(255, 255, 255, 0.5) !important;\n    }\n\n\n    /*Bouttons*/\n    .nr-dashboard-theme .nr-dashboard-button .md-button {\n        background-color: rgba(255,255,255,.1) !important;\n    }\n    .md-button {\n        border-radius: 10px !important;\n    }\n\n\n    /*Dropdown menu*/\n    .nr-dashboard-theme md-select-menu{\n        background-color: rgba(40,85,165,1) !important;\n    }\n    .nr-dashboard-theme md-select-menu, .nr-dashboard-theme md-select-menu md-option {\n        background-color: transparent !important;\n    }\n    .nr-dashboard-theme .md-select-menu-container {\n        border-radius: 10px !important;\n        border: none !important;\n    }\n    .nr-dashboard-theme md-select-menu md-option[selected] {\n        color: white !important;\n        background-color: #1a3566 !important;\n    }\n\n    /*Template*/\n    md-card>img, md-card>md-card-header img, md-card md-card-title-media img {\n        border-radius: 10px !important;\n    }\n\n    /* Color picker text BG */\n    .nr-dashboard-theme .color-picker-input-wrapper > input {\n        color: white !important;\n        background-color: transparent !important;\n    }\n\n</style>","storeOutMessages":true,"fwdInMessages":true,"resendOnRefresh":false,"templateScope":"global","x":420,"y":340,"wires":[[]]},{"id":"d783cb980c3979fc","type":"ui_group","name":"Demo","tab":"0449b3b1fea99d52","order":1,"disp":true,"width":"6","collapse":false},{"id":"0449b3b1fea99d52","type":"ui_tab","name":"Demo","icon":"dashboard","disabled":false,"hidden":false}]


## Theme de ses morts fait par Bynaris

SOON
