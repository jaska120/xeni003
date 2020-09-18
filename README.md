# Cover basic commands

Open Command prompt / shell

- On Mac we will use `Terminal.app`
- On Windows we will use `cmd.exe`

## Show system information (Jaakko M)

Mac:

```
sw_vers
```

Windows:

```
systeminfo
```

## Check in which directory you are on (Jaakko R)

Mac:

```
pwd
```

Windows:

```
echo %CD%
```

## Naviagte to desktop (Mikael)

Mac:

```
cd ~/Desktop
```

Windows:

```
cd %userprofile%/Desktop
```

## Create a folder in desktop (Jaakko M)

Mac:

```
mkdir xeni003
```

Windows:

```
mkdir xeni003
```

## Create index.txt on desktop (Jaakko R)

Mac:

```
touch index.txt
```

Windows:

```
type nul>index.txt
```

## Move index.txt to created folder (Mikael)

Mac:

```
mv index.txt xeni003/index.txt
```

Windows:

```
move index.txt xeni003/index.txt
```

## Change to created directory and list (Jaakko M)

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

## Rename index.txt -> index.html (Jaakko R)

Mac:

```
mv index.txt index.html
```

Windows:

```
move index.txt index.html
```

## Copy html markup (Mikael)

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

## Open index.html in command line (windows in program) (Jaakko M)

Mac:

```
nano index.html
```

Windows:

```
Notepad index.html
```

## Paste copied html markup (Jaakko R)

Save file

- On Mac you should press in following sequence: ctrl + x, Y, Enter
- On Windows you should save the file as normally with notepad

## Output file contents of created file (Mikael)

Mac:

```
cat index.html
```

Windows:

```
type index.html
```

## Find path to file (Jaakko M)

Mac:

```
realpath index.html
```

Windows:

```
echo %CD%/index.html
```

## Open in browser (Jaakko R)

Copy the path from previous command and paste it in to a browser of your choice.

## Remove created directory and files in there (Mikael)

Mac:

```
rm -r ~/Desktop/xeni003
```

Windows:

```
rmdir %userprofile%/Desktop/xeni003
```
