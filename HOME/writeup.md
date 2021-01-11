## 1
Brower Official URL: https://realworldctf.com/ <br>
F12 -> Choose Network <br>
F5 to Reload This Page <br>
Find signin.baacf08.jpg request <br>
Check the picture. <br>
this picture content (hit):
```python
from pwn import *
io = remote('home.realworldctf.com', 1337)
```

## 2
Write a python file:
```python
from pwn import *
io = remote('home.realworldctf.com', 1337)
io.interactive()
```
Run it. <br>
You will get flag!
