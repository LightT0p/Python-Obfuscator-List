# Hello
## This repo is for educational purposes only...
### I do not condone or endorse any illegal activities / the obfuscators being used for

Notation:
| Emoji Corresponding  | Hardness of deobfuscation |
|     -------------    |       -------------       |
|  🔴  |  Easy     |
|  🟡  |  Medium   |
|  🔵  |  Hard     |
|  🟢  |  Harder   |
|  🟣  |  Insane   |

1. Oxyry obfuscator:
  | Link: https://pyob.oxyry.com/
  | SRC: None
  |_ Description: Oxyry obfuscator is a barebone obfuscator, all it really do is making you code compact ( remove moving comments, white spaces and new lines ) and just rename the variables.
  |_ The code is still very readable, just rename all the var to like "var1", "var2" etc, so the code is less confusing, no string encryption WHATSOEVER. Don't recommend
  | De-Obfuscator: Do you really need one ?
  | Notation:  🔴

2. Pyobfuscate
  | Link: https://pyobfuscate.com/pyd
  | SRC: None
  |_ Description: pyobfuscate.com is a python obfuscator that plays on changing variables name.
  |_ As of right know, i know that there are at least 2 steps of obfuscation, first one being decompressing a zlib compressed string from a hex string.
  |_ The 2nd step allocate new name to built-in python key words ( ex: ____=dict, ______=str ) etc
  | De-Obfuscator: https://github.com/KhanhNguyen9872/deobf_pyobfuscate.com ( I dont know if it works on large scripts ) 
  | Notation:  (🔴 if you have a deobfuscator) else 🔵

3. Hyperion
  | Link: https://github.com/billythegoat356/Hyperion
  | SRC: https://github.com/billythegoat356/Hyperion/blob/main/hyperion.py
  |_ Description: Hyperion is a powerfull obfuscator that have more than a 10 steps obfuscation system
  | De-Obfuscator: https://github.com/xKiian/Hyperion-deobfuscator
  | Notation: (🔴 if you have a deobfuscator) else 🟢

4. Specter
  | Link: https://github.com/billythegoat356/Specter
  | SRC: 
  |_ Description: Great python obfuscator with an anti-skid, 3 steps of obfuscation
  | De-Obfuscator: https://github.com/0verp0wer/Spectered
  |_ Notation: (🔴 if you have a deobfuscator) else 🟢
