# Scripting docs
TES3MP [](http://docs.tes3mp.com/)

# Table of contents
1. [Introduction](#introduction)
2. [GUI](#GUI)
    1. [Dynamic GUI IDs](#dynamicguiid)
3. [Another paragraph](#paragraph2)

## Introduction <a name="introduction"></a>
Some introduction text, formatted in heading 2 style

## GUI <a name="GUI"></a>
These are some usefull tidbits when using GUIs.

### Dynamic GUI IDs <a name="dynamicguiid"></a>
Due to how the guiHelper is scripted the best way to add a new guiID is this:
```lua
guiHelper.ID["TEXTNAME"] = tableHelper.getCount(guiHelper.ID) + 1
```
