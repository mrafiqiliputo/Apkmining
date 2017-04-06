# Apkmining
mining V0.1a
c.setopt(c.URL, 'https://api.github.com/repos/mrafiqiliputo/Apkmining')
for p in myobj:
    if "assets" in p:
        for asset in p['assets']:
            print (asset['name'] + ": " + str(asset['download_count']) +
                   " downloads")
