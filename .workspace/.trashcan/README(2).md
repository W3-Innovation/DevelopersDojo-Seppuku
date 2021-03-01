<br>

<div style="padding: 12px; border-top: 1px solid #404040; border-bottom: 1px solid #404040; min-width: 620px; max-width: 900px;background: #0000003D">

# <b style=" padding-left: 24%; color: #EE0C38; center;"> Developer's Dojo: Seppuku</b>

- ##### &nbsp; &nbsp; **Repository: https://github.com/W3-Innovation/DevelopersDojo-Seppuku**
- ##### &nbsp; &nbsp; **Developer: A. Jay Chambers | W3-Innovation**
- ##### &nbsp; &nbsp; **Email: AChambers.W3Innovation@gmail.com**

</div>

<br>

<span style="color: #0C809A; font-size: 17px;">

| &nbsp; README'S TABLE OF CONTENTS |     |
| --------------------------------- | --- |

| &nbsp; -01- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -02- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; CONTEMPORARY THEMES &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -03- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -04- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -05- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -06- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -07- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |
| &nbsp; -08- &nbsp;\| &nbsp;<span style="color: crimson; font-size: 14px">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ABOUT SEPUKU &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span> |

</span>

<br>

## <i style=" color: crimson;">About Seppuku:</i>

<hr style="border: none; height: 1px; background: #A00020;">

&nbsp; &nbsp; &nbsp; &nbsp; ‘Developer’s Dojo: Seppuku’ is part of a series of themes that I am currently working on, and is the first of three themes that I plan to publish. Seppuku is a Dark theme that uses a quintessential bichromatic color palette for it’s core design, which consists of 2 complementary colors, and a single neutral color, and is the source from which all of the colors used in styling the editor are derived. color grouping Seppuku’s entire color (The basic palette is below this paragraph ). Seppuku is colored using several color-schemes, not just the editor’s color-scheme mentioned above. There are color-schemes for Highlight the syntax within scripts (squiggly-lines, warnings, ect...), version-control decorations (modified resources, added resource, untracked resources, ect...), resource status (Problem-errors, Problem-Info, Problem-Warning, auto fix, ect...), and more. This is a lot of information, more than a user needs to know really. I have been working my way towards a point which is this; through much work I have documented and categorized most all of the colors used to color the Seppuku theme, thus giving me the ability to create documentation for seppuku users to reference. Because every theme varies in color there is little to no consistency in editor highlighting color definitions, one editor may used a yellow green to display an error, where others use a true #f00 red, and it is because of this that themes should offer documentation, stating what colors they are using for features like version control highlighting, and status notification icons in the problems panel (these are 2 examples of several that could be listed). Even though there is good reason to document a themes colors in the readme file, or a separate document, most themes don't and the ones that do, do it minimally. The reason that the majority of themes lack a good color reference is an understandable one, it takes a lot more time then perhaps it is worth, the value of such a thing is subject to opinion. Personally I couldn’t imagine releasing the theme without informing users what colors I chose to use, where I used them and why, it seems like it's my duty to do that for the open source community who will be using my theme, so below I give to you, a proper highlight reference for Developer’s Dojo: Seppuku.

<br>

<br>

## <i style=" color: crimson;">VSCode & It's Themes:</i>

<hr style="border: none; height: 1px; background: #A80034;">

&nbsp; &nbsp; &nbsp; &nbsp; VS-Code’s latest version (at the time of writing this) is: (version 1.53.2). Over the last 5 years VSCode has made more progress than any of the other editors/IDEs out there, which is great in every way possible, except one, many of VSCodes newly added features have rendered a large number of VSCode extensions deprecated, and this includes themes. Though you may never see a theme alert users that its source JSON file is loaded with deprecated properties, but I assure you, if your theme is older, it is highly likely that the themes JSON file is loaded with deprecated JSON properties, and/or textmate blocks. Nearly every time I pop-open a JSON file belonging to a popular theme that has 75k downloads plus, the document bleeds yellow. More often than not there are so many deprecated properties, that it would just be easier to create a new theme than fix the old one.

<br>

<br>

<i style=" color: crimson; font-size: 18px">CONTEMPORARY FEATURES:</i>

<hr style="border: none; height: 1px; background: #A80034;">

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; As of January 2021 VSCode released a new feature that I really love. For those using repositories, (wouldn’t that mean everyone? lol), it's a very helpful, and aesthetically beautiful addition to an already awesome editor. If you don't know about it, it's called Tab-Decorations, and it uses the already existing version control decorating properties, GitDecorations. When a theme custom styles these, and a user equips them, the new theme will look ages more advanced than the old deprecated themes. Below I list the configuration I use to equip the decorations. Another aesthetic feature that new themes should be using are Semantic Tokens, for code highlighting. You can select syntax in ways that we use to wish we could, and now we can.  
<br><br>

### <i style="color: crimson;">Boo Far!</i>

---

#### foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo...

<br><br>

### <i style="color: crimson;">Boo Far!</i>

---

#### foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo...

<br><br>

### <i style="color: crimson;">Boo Far!</i>

---

#### foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo...

<br><br>

### <i style="color: crimson;">Boo Far!</i>

---

#### foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo... foobar... Boo Far!!! Far Boos??? Nooooooooooooo...
