# French language steming API
This [exemple](https://5inq.fr/api/stems/?text=Lorsque+le+cours+d%27eau+atteint+son+profil+d%27%C3%A9quilibre,+il+cesse+de+creuser.+La+vall%C3%A9e,+qu%27il+a+contribu%C3%A9+%C3%A0+cr%C3%A9er,+reste+%C3%A9troite+en+raison+de+la+r%C3%A9sistance+des+roches+des+versants+qui+pr%C3%A9sentent+des+pentes+in%C3%A9gales+les+calcaires+forment+des+corniches,+les+marnes+des+replats) returns:
```JSON
{
  "query":"Lorsque le cours d'eau atteint son profil d'\u00e9quilibre, il cesse de creuser. La vall\u00e9e, qu'il a contribu\u00e9 \u00e0 cr\u00e9er, reste \u00e9troite en raison de la r\u00e9sistance des roches des versants qui pr\u00e9sentent des pentes in\u00e9gales (les calcaires forment des corniches, les marnes des replats",
  "stems":{
    "fr":"lorsqu cour eau att profil equilibr ces creu vallee contribu cre rest etroit raison resist roch vers pres pent inegal calcair form cornich marn replat"
  }
}
```
