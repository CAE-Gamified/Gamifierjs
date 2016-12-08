# Gamifierjs
Gamifierjs library to extend community application with gamification feature

To use Gamifierjs library in your community application, you need to 

- Clone this repository
- Copy *gamification* folder
- Include Gamifierjs files in widget.xml :
```
<script type="text/javascript" src="{URL path}/gamification/aop.pack.js"></script>
<script type="text/javascript" src="{URL path}/gamification/gamifier.js"></script>
<script type="text/javascript" src="{URL path}/gamification/oidc-widget.js"></script>
```

- Create new global variables in your JavaScript application file that specify game ID and end point URL of Gamification Visualization Service in your application js file :
```
var gameId = '<GAME_ID>', epURL = '<END_POINT_URL>';

For example:

var gameId = 'todolistapp', epURL = 'http://gaudi.informatik.rwth-aachen.de:8086/';
```

- Call trigger action wherever you need in your code with this line :
```
Gamifier.triggerAction('<actionId>');

For example:

Gamifier.triggerAction('addAction');
```
