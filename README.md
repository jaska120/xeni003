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
mv index.txt xeni003/index.txt
```

## Change to created directory and list

Mac:

```
cd xeni003
ls
```

Windows:

```
cd xeni003
dir
```

## Rename index.txt -> index.html

Mac:

```
mv index.txt index.html
```

Windows:

```
mv index.txt index.html
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

## Open index.html in command line

Mac:

```
nano index.html
```

Windows:

```
nano index.html
```

## Paste copied html markup

## Save file

- Press ctrl + x
- Press Enter
- Press Enter

## Output file contents of created file

Mac:

```
cat index.html
```

Windows:

```
cat index.html
```

## Find path to file

Mac:

```
realpath index.html
```

Windows:

```

```

## Open in browser
