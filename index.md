# Donnerskopf WorkAdventure

Das Wochenende ist schon ganz gut gefüllt. Von einem Meeting ins nächste - da kommt Freude auf! Aber was wäre das Netzwerktreffen ohne Doko? Ohne kurze Kaffeepausen, Kellerbar und Klönen? Wir laden euch ein aufs digitale DokoAdventure. Leute die sowieso da sind...

<script>
            window.onload = function() {
                var path = window.location.pathname;
                if (path.endsWith('index.html')) {
                    path = path.substr(path, path.length - 'index.html'.length);
                }
                var url = 'https://play.workadventu.re/_/global/'+window.location.host+path+'map.json';
                document.getElementById('mapLink').href = url;
                document.getElementById('mapLink').innerText = url;
            };
</script>

Los geht's zum DokoAdventure: <a id="mapLink" href=""></a>

<iframe width="315" height="560" src="https://www.youtube.com/embed/S8C6BqN05ro" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
