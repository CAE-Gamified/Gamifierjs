# Gamifierjs
Gamifierjs library to extend community application with gamification feature

To use Gamifierjs library in your community application, you need to 

- Include Gamifierjs files in widget.xml :
```
<script type="text/javascript" src="{URL path}/gamifier.js"></script>
<script type="text/javascript" src="{URL path}/oidc-widget.js"></script>
```

- Specify application ID and end point URL in Gamifier.js file :
```
appId = '$Application_Id$',
epURL = '$EP_URL$'
```

- Call trigger action wherever you need in your code with this line :
```
Gamifier.triggerAction('{actionId}');
```
