# Cover basic commands

Open Command prompt / shell

- On Mac we will use `Terminal.app`
- On Windows we will use `cmd.exe`

## 1. Show system information (Jaakko M)

Mac:

```
sw_vers
```

Windows:

```
systeminfo
```

## 2. Check in which directory you are on (Jaakko R)

Mac:

```
pwd
```

Windows:

```
echo %CD%
```

## 3. Naviagte to desktop (Mikael)

Mac:

```
cd ~/Desktop
```

Windows:

```
cd %userprofile%/Desktop
```

## 4. Create a folder in desktop (Jaakko M)

Mac:

```
mkdir xeni003
```

Windows:

```
mkdir xeni003
```

## 5. Create index.txt on desktop (Jaakko R)

Mac:

```
touch index.txt
```

Windows:

```
type nul>index.txt
```

## 6. Move index.txt to created folder (Mikael)

Mac:

```
mv index.txt xeni003/index.txt
```

Windows:

```
move index.txt xeni003/index.txt
```

## 7. Change to created directory and list (Jaakko M)

Mac:

```
cd xeni003
```

```
ls
```

Windows:

```
cd xeni003
```

```
dir
```

## 8. Rename index.txt -> index.html (Jaakko R)

Mac:

```
mv index.txt index.html
```

Windows:

```
move index.txt index.html
```

## 9. Copy html markup (Mikael)

```
<html>
  <head>
    <title>XENI003</title>
  </head>
  <body>
    <h1>Hello world</h1>
  </body>
</html>
```

## 10. Open index.html in command line (windows in program) (Jaakko M)

Mac:

```
nano index.html
```

Windows:

```
Notepad index.html
```

## 11. Paste copied html markup (Jaakko R)

Save file

- On Mac you should press in following sequence: ctrl + x, Y, Enter
- On Windows you should save the file as normally with notepad

## 12. Output file contents of created file (Mikael)

Mac:

```
cat index.html
```

Windows:

```
type index.html
```

## 13. Find path to file (Jaakko M)

Mac:

```
realpath index.html
```

Windows:

```
echo %CD%/index.html
```

## 14. Open in browser (Jaakko R)

Copy the path from previous command and paste it in to a browser of your choice.

## 15. Remove created directory and files in there (Mikael)

Mac:

```
rm -r ~/Desktop/xeni003
```

Windows:

Answer yes when prompted

```
rmdir %userprofile%\Desktop\xeni003 /s
```

## 16. Styling

Let's make the headline blue!

```
<html>
  <head>
    <title>XENI003</title>
  </head>
  <body>
    <h1 style="color:blue;">Hello world</h1>
  </body>
</html>
```
