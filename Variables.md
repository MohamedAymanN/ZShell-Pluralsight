<img width="1214" alt="image" src="https://user-images.githubusercontent.com/45315180/112444726-075ae280-8d57-11eb-8021-614adaf12933.png">
<img width="1322" alt="image" src="https://user-images.githubusercontent.com/45315180/112444880-2c4f5580-8d57-11eb-95a9-e203fe126266.png">
<img width="1317" alt="image" src="https://user-images.githubusercontent.com/45315180/112444953-48eb8d80-8d57-11eb-9d07-132c6966d76f.png">
<img width="1310" alt="image" src="https://user-images.githubusercontent.com/45315180/112445025-5c96f400-8d57-11eb-987e-727e19d31ae1.png">

## `set` has local shell variables, `env` has environment variables
## we can `export` local variables to set them in the `env` scope
## We can use the variable for a certain command as : `EDITOR=vim crontab -e`
# Power of declare
<img width="1212" alt="image" src="https://user-images.githubusercontent.com/45315180/112446161-96b4c580-8d58-11eb-84fa-2244e51d74d2.png">
<img width="1307" alt="image" src="https://user-images.githubusercontent.com/45315180/112446394-d1b6f900-8d58-11eb-96b4-bb7646552ba3.png">
```bash
Add variable to env
declare -x <varname>

Remove variable from env
declare +x <varname>
```
<img width="1312" alt="image" src="https://user-images.githubusercontent.com/45315180/112451192-e3e76600-8d5d-11eb-94c1-1043ea592a47.png">
<img width="1312" alt="image" src="https://user-images.githubusercontent.com/45315180/112451538-4b051a80-8d5e-11eb-80d9-daf452e8c9fb.png">
<img width="1187" alt="image" src="https://user-images.githubusercontent.com/45315180/112451717-7b4cb900-8d5e-11eb-916e-aea3eee13da9.png">
## Use `-r` flag to make variable in declare (read_only)
# Using conditions
<img width="1357" alt="image" src="https://user-images.githubusercontent.com/45315180/112453611-8c96c500-8d60-11eb-94b2-3ec2a2158f4a.png">
<img width="1297" alt="image" src="https://user-images.githubusercontent.com/45315180/112453749-aa642a00-8d60-11eb-9e80-f5461e27437a.png">
<img width="1332" alt="image" src="https://user-images.githubusercontent.com/45315180/112454238-265e7200-8d61-11eb-8406-659393911f6b.png">
<img width="1325" alt="image" src="https://user-images.githubusercontent.com/45315180/112454358-455d0400-8d61-11eb-81f8-12dfc3220012.png">
<img width="1330" alt="image" src="https://user-images.githubusercontent.com/45315180/112454458-5e65b500-8d61-11eb-93e1-b33cc924cdc6.png">
## Taking user input
```bash
read <varname>
```

## Comparing Strings
<img width="1325" alt="image" src="https://user-images.githubusercontent.com/45315180/112457083-15fbc680-8d64-11eb-8526-09b86a18a62f.png">
<img width="1316" alt="image" src="https://user-images.githubusercontent.com/45315180/112457207-3166d180-8d64-11eb-8d4b-e02d76fd29fa.png">
<img width="1316" alt="image" src="https://user-images.githubusercontent.com/45315180/112457367-5ce9bc00-8d64-11eb-8fcb-129b0776dbed.png">
### Use `escape` + `.` to get the defined var
<img width="595" alt="image" src="https://user-images.githubusercontent.com/45315180/112458086-147ece00-8d65-11eb-92e3-711a92c513c1.png">
## Test Command
<img width="1316" alt="image" src="https://user-images.githubusercontent.com/45315180/112458812-e221a080-8d65-11eb-93a2-19e16046410e.png">
```bash
[[-f <filename>]]: Tests for a file
[[-d <filename>]]: Tests for a directory
[[-L <filename>]]: Tests for a symbolic link
[[-e <filename>]]: Tests for existince of a file
[[-r -w -x  <filename>]]: Tests for permissions
[[-k <filename>]]: Tests for the sticky bit (tmp directory)
```

## Use `type` to find each commands type

<img width="1316" alt="image" src="https://user-images.githubusercontent.com/45315180/112457367-5ce9bc00-8d64-11eb-8fcb-129b0776dbed.png">
