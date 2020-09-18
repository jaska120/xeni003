# Cover basic commands

Open Command prompt / shell

Show system information

Mac:

```
sw_vers
```

Windows:

```
systeminfo
```

## Check in which directory you are on

Mac:

```
pwd
```

Windows:

```
echo %CD%
```

## Naviagte to desktop

Mac:

```
cd ~/Desktop
```

Windows:

```
cd %userprofile%/Desktop
```

## Create a folder in desktop

Mac:

```
mkdir xeni003
```

Windows:

```
mkdir xeni003
```

## Create index.txt on desktop

Mac:

```
touch index.txt
```

Windows:

```
type nul>index.txt
```

## Move index.txt to created folder

Mac:

```
mv index.txt xeni003/index.txt
```

Windows:

```
move index.txt xeni003/index.txt
```

## Change to created directory and list

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

## Rename index.txt -> index.html

Mac:

```
mv index.txt index.html
```

Windows:

```
move index.txt index.html
```

## Copy html markup

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

## Open index.html in command line (windows in program)

Mac:

```
nano index.html
```

Windows:

```
Notepad index.html
```

## Paste copied html markup

## Save file

- On Mac you should press in following sequence: ctrl + x, Y, Enter
- On Windows you should save the file as normally with notepad

## Output file contents of created file

Mac:

```
cat index.html
```

Windows:

```
type index.html
```

## Find path to file

Mac:

```
realpath index.html
```

Windows:

```
echo %CD%/index.html
```

## Open in browser

Copy the path from previous command and paste it in to a browser of your choice.
