# PATCHED

# captchaCodeMakerV2
I believe this method of getting captchas is patched/broken now</b><br>
Make Roblox's signup funcaptcha code so you can send to discord bots (REMADE)<br>
![](https://komarev.com/ghpvc/?username=captchaCodeMakerV2&label=Repo+Views)

### Example on how to get the code after
Better example [link](https://github.com/Roblox-Thot/captchaCodeMakerV2/blob/main/example/sign%20up.py)<br>
```py
import base64
code = "Code here"
decoded = base64.b64decode(code).decode('utf-8').split(',')
captchaId = decoded[0]
captchaToken = decoded[1]
print(f'Captcha ID: {captchaId}')
print(f'Captcha Token: {captchaToken}')
```
