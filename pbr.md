Im Studienfach Physically Based Rendering, war die Aufgabe ein Arnold-Material zu erstellen.
Ich entschied mich dazu Glut aus Holzkohle umzusetzen.

![img](pbr.jpg)

Wichtig war es, dass die Glut drei Merkmale aufweist.
- Große Flächen, um die großen Holzkohlestücke darzustellen. Benutzt wurde hierfür eine Cellular-Node sowie eine Smoke-Node als Distortion um nicht zu glatte Kanten zu erhalten
- Innerhalb dieser Großen Flächen sollten noch kleinere Flächen zu sehen sein. Es wurden die selben Nodes wie zuvor benutzt, lediglich das Tiling wurde erhöht.
- Eine Holzmaßerung, die durch die Advanced Wood Map zum Vorschein kam.

Das File für das Material ist [hier](pbr.max) zu finden.
