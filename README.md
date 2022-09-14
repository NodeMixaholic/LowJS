# LowJS
"Pyeta! There is no Sans! Wake up!"

## What is LowJS?

LowJS provides web support for, and is the wife project of Pyeta. Pyeta, but made for PyScript

```
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js"></script> 
<py-script>
import urllib

def deineLowJS():
  ljslink = "https://raw.githubusercontent.com/NodeMixaholic/LowJS/main/lowjs.py"
  f = urllib.urlopen(ljslink)
  lowjs = f.read()
  exec(lowjs)
  
# And then we interface with LowJS' Pyeta subsystem like so...
runPyeta("""console.writeLine('Hello, world!')
console.writeLine('Note that this does not work with Pyetas Panda3D/PyGame tools.')""")

</py-script> 
```
