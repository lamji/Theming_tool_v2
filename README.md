## Theming Tool

Theming tool for frappe

#### Installing
```
Theming tool for frappe

#### Installing
```

$ bench set-config developer_mode 1

$ bench get-app https://github.com/lamji/Theming_tool_v2.git

$ bench --site erpnext install-app theming_tool

$ sudo chmod -R 777 /sites/assets/erpnext

$ sudo /opt/bitnami/ctlscript.sh restart
```
#### How To Use
1- Create "Element" and insert it's "class" name example: Nav-bar class is ".navbar-default"

2- Create "System Font" and attach the font file.

3- Go to "Theme Settings" and select your font, logo, and in "ELEMENTS STYLES" table insert your element then chose a color GO.
NOTE: here I just add "background-color" attribute I'm willing to add more in the future.

4- GO and hit SAVE.

FOR IMAGES & DISCUSSION GO TO THIS [LINK](https://discuss.erpnext.com/t/frappe-erpnext-theming-tool/67500).
  
#### License

MIT
