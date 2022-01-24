# Updated New Vesion PySimpleGUI


![image](https://user-images.githubusercontent.com/88630056/150878248-c225a437-486d-47ee-b913-53c62efe105f.png)




# Keys.py Random&Sequential keys.lol

My Version of KEYS.LOL made my Mizogg https://mizogg.co.uk

keys.py Sequential scan and keysr.py Random scan

I hope you all enjoy. Bit is Python’s fastest Bitcoin library using Block Chain API to query 256 addresses.

Test it here : https://replit.com/@Mizogg/keyspy-keyslol?v=1

## To Install
```
pip install bit
pip install rich
```
## To Start
```
python keys.py
```
## Example Puzzle 64-160 Below
```
 -----------------KEYS.LOL----------------------
                 Starting search...
                Using Block Chain API...
 -----------------KEYS.LOL----------------------
 ℹ️ Start search... Pick Range to start (Min=0 Max=256) ℹ️
 ✅ Start range in BITs (Puzzle StartNumber) ✍️ -> 64
 ⛔️ Stop range Max in BITs (Puzzle StopNumber)✍️ -> 160
⏳Starting search... Please Wait ⏳
 [1] ------------------------
🔁 Total Checked 👇[256]
😒😞😔😟😕 Bitcoin Address Compressed : 1J88acaLhCnSD8HojSBpC2Y1JrN7KcEVcZ
😒😞😔😟😕 Bitcoin Address UnCompressed : 1HCykLda8Ui4NjYUEuUr5xnQCrwpRHexAV
🔑 Private Key (HEX) : 000000000000000000000000c7d56cb1b5e38264c1798d01bcc52f727dd370c5
🔑 Private Key (DEC) : 1140848690719862226484188065888594519092494561477
🔑 PrivateKey (wif) Compressed : KwDiBf89QgGbjEhKniuicoC1tJzTC3QoSFiQQSDBpsyCoUma2EJU
🔑 PrivateKey (wif) UnCompressed : 5HpHagT65TZzG1PH3Cm7iBvFFLwFYW6PknUWKT6w7KLz3qzgvGt
📋 Page Number : [8912880396248923644407719264754644680410113762]
🌩Loading 10 Seconds :■□□□□□□□□□□□□□□□□□□□  5% Traceback (most recent call last):
```
![image](https://user-images.githubusercontent.com/88630056/144724892-2c4b22ad-677c-478f-84bf-aaa99efaa0b1.png)
```
my_colours = [W, R, G, O, B, P]
icons= ['⏳', 'ℹ️', '✅', '⛔️', '🔁', '🔑', '💸', '😔', '🌍', '✍️', '🚌', '👇', '📋', '📣', '🤩','😀', '😃', '😄', '😁', '😆', '😅', '😂', '🤣', '🥲', '☺️', '😊', '😇', '🙂', '🙃', '😉', '😌', '😍', '🥰', '😘', '😗', '😙', '😚', '😋', '😛', '😝', '😜', '🤪', '🤨', '🧐', '🤓', '😎', '🥸', '🤩', '🥳', '😏', '😒', '😞', '😔', '😟', '😕', '🙁', '☹️', '😣', '😖', '😫', '😩', '🥺', '😢', '😭', '😤', '😠', '😡', '🤬', '🤯', '😳', '🥵', '🥶', '😱', '😨', '😰', '😥', '😓', '🤗', '🤔', '🤭', '🤫', '🤥', '😶', '😐', '😑', '😬', '🙄', '😯', '😦', '😧', '😮', '😲', '🥱', '😴', '🤤', '😪', '😵', '🤐', '🥴', '🤢', '🤮', '🤧', '😷', '🤒', '🤕', '🤑', '🤠', '😈', '👿', '👹', '👺', '🤡', '💩', '👻', '💀', '☠️', '👽', '👾', '🤖', '🎃', '😺', '😸', '😹', '😻', '😼', '😽', '🙀', '😿', '😾', '👋', '🤚', '🖐', '✋', '🖖', '👌', '🤌', '🤏', '✌️', '🤞', '🤟', '🤘', '🤙', '👈', '👉', '👆', '🖕', '👇', '☝️', '👍', '👎', '✊', '👊', '🤛', '🤜', '👏', '🙌', '👐', '🤲', '🤝', '🙏', '✍️', '💅', '🤳', '💪', '🦾', '🦵', '🦿', '🦶', '👣', '👂', '🦻', '👃', '🫀', '🫁', '🧠', '🦷', '🦴', '👀', '👁', '👅', '👄', '💋', '🩸', '🐒', '🐔', '🐧', '🐦', '🐤', '🐣', '🐥', '🦆', '🦅', '🦉', '🦇', '🐺', '🐗', '🐴', '🦄', '🐝', '🪱', '🐛', '🦋', '🐌', '🐞', '🐜', '🪰', '🪲', '🪳', '🦟', '🦗', '🕷', '🕸', '🦂', '🐢', '🐍', '🦎', '🦖', '🦕', '🐙', '🦑', '🦐', '🦞', '🦀', '🐡', '🐠', '🐟', '🐬', '🐳', '🐋', '🦈', '🐊', '🐅', '🐆', '🦓', '🦍', '🦧', '🦣', '🐘', '🦛', '🦏', '🐪', '🐫', '🦒', '🦘', '🦬', '🐃', '🐂', '🐄', '🐎', '🐖', '🐏', '🐑', '🦙', '🐐', '🦌', '🐕', '🐩', '🦮', '🐕‍🦺', '🐈', '🐈‍⬛', '🪶', '🐓', '🦃', '🦤', '🦚', '🦜', '🦢', '🦩', '🕊', '🐇', '🦝', '🦨', '🦡', '🦫', '🦦', '🦥', '🐁', '🐀', '🐿', '🦔', '🐾', '🐉', '🐲', '🌵', '🎄', '🌲', '🌳', '🌴', '🪵', '🌱', '🌿', '☘️', '🍀', '🎍', '🪴', '🎋', '🍃', '🍂', '🍁', '🍄', '🐚', '🪨', '🌾', '💐', '🌷', '🌹', '🥀', '🌺', '🌸', '🌼', '🌻', '🌞', '🌝', '🌛', '🌜', '🌚', '🌕', '🌖', '🌗', '🌘', '🌑', '🌒', '🌓', '🌔', '🌙', '🌎', '🌍', '🌏', '🪐', '💫', '⭐️', '🌟', '✨', '⚡️', '☄️', '💥', '🔥', '🌪', '🌈', '☀️', '🌤', '⛅️', '🌥', '☁️', '🌦', '🌧', '⛈', '🌩', '🌨', '❄️', '☃️', '⛄️', '🌬', '💨', '💧', '💦', '☔️', '☂️', '🌊', '🌫', '⏰', '💰', '🎅🏻', '🎄', '🎁', '🎶']

animation = ["□□□□□□□□□□□□□□□□□□□□  0%","■□□□□□□□□□□□□□□□□□□□  5%","■■□□□□□□□□□□□□□□□□□□ 10%","■■■□□□□□□□□□□□□□□□□□ 15%","■■■■□□□□□□□□□□□□□□□□ 20%","■■■■■□□□□□□□□□□□□□□□ 25%","■■■■■■□□□□□□□□□□□□□□ 30%","■■■■■■■□□□□□□□□□□□□□ 35%","■■■■■■■■□□□□□□□□□□□□ 40%","■■■■■■■■■□□□□□□□□□□□ 45%","■■■■■■■■■■□□□□□□□□□□ 50%","■■■■■■■■■■■□□□□□□□□□ 55%","■■■■■■■■■■■■□□□□□□□□ 60%","■■■■■■■■■■■■■□□□□□□□ 65%","■■■■■■■■■■■■■■□□□□□□ 70%","■■■■■■■■■■■■■■■□□□□□ 75%","■■■■■■■■■■■■■■■■□□□□ 80%","■■■■■■■■■■■■■■■■■□□□ 85%","■■■■■■■■■■■■■■■■■■□□ 90%","■■■■■■■■■■■■■■■■■■■□ 95%","■■■■■■■■■■■■■■■■■■■■100%"]
```
```
console.print(" [yellow]-----------------KEYS.LOL----------------------[/yellow]")
console.print("[yellow]                 Starting search...[/yellow]")
console.print("[yellow]                Using Block Chain API...[/yellow]")
console.print(" [yellow]-----------------KEYS.LOL----------------------[/yellow]")
console.print("[yellow] ℹ️ Start search... Pick Range to start (Min=0 Max=256) ℹ️ [/yellow] ")
```
![image](https://user-images.githubusercontent.com/88630056/144724912-18792767-1d49-4e53-aa2b-394edaae9a38.png)


![image](https://user-images.githubusercontent.com/88630056/144724934-a2686ccc-9aa1-499e-bbd8-c1a5aadaa804.png)

keys.py

FULL Results Sequential Scan 128 Results per page/scan. Checks all information final balance, Transactions, Total Received and Total sent. Saves the page number of wallet found. Blockchain.info/multiaddr join query 256 addresses. 10 Seconds for sleep so that the API does not block you. 
# Good Luck and Happy Hunting. Made by mizogg.co.uk

Also Check out my other Version on https://mizogg.co.uk/python-bitcoin-balance/


# Donations 3P7PZLbwSt2bqUMsHF9xDsaNKhafiGuWDB 
