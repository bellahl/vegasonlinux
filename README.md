## how to get vegas 11 pro on linux (revamped)

### this is a simpler version of https://javier164.github.io/guide.html

### this tutorial is focused towards chromebooks, but this also works with linux and macos!

----

### requirements:

64bit chromeos (or an intel/amd proccesor)

around 5gb of free space

wine installed (https://tinyurl.com/winechrome)

winetricks installed

```
sudo wget 'https://raw.githubusercontent.com/Win... -O /usr/local/bin/winetricks

sudo chmod +x /usr/local/bin/winetricks
```

patience

---

**step 1**: download these files - https://tinyurl.com/vegaspro

**step 2**: import into "linux files" (found on the chromeos **files** app)

**step 3**: go into your terminal

**step 4**: paste this into your terminal:
```
winetricks dotnet20 dotnet35sp1
```
follow any prompted steps!!

**step 5**: open installer (when net is done)

**step 6**: follow all promped steps

**step 7**: enjoy!! :D
