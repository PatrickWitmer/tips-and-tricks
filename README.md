# tips-and-tricks
Tips and Tricks


Change the volume of bandcamp in the dev tools console, via the DOM:

`let audios = [...document.getElementsByTagName('audio')];  
audios.forEach(audio => audio.volume = 0.5) // lower volume 50%.`
