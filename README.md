# Gamifierjs
Gamifierjs library to extend community application with gamification feature

To use Gamifierjs library in your community application, you need to 

- Include Gamifierjs files in widget.xml :
```
<script type="text/javascript" src="{URL path}/aop.pack.js"></script>
<script type="text/javascript" src="{URL path}/Gamifier.js"></script>
<script type="text/javascript" src="{URL path}/oidc-widget.js"></script>
```

- Create new variables that specify game ID and end point URL of Gamification Visualization Service in your application js file :
```
var gameId = '<GAME_ID>', epURL = '<END_POINT_URL>';
```

- Call trigger action wherever you need in your code with this line :
```
Gamifier.triggerAction('<actionId>');
```
