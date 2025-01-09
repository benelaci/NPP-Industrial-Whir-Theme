# Industrial Whir ▪ Theme for Notepad++

![Industrial Whir theme for Notepad++, example 1](https://i.ibb.co/FqWywhj/Industrial-Whir-example-1.png)
![Industrial Whir theme for Notepad++, example 2](https://i.ibb.co/kHxG1JV/Industrial-Whir-example-2.png)
![Industrial Whir theme for Notepad++, example 3](https://i.ibb.co/sPzgHJ7/Industrial-Whir-example-3.png)

# Description

Industrial colors, adjusted in great detail, creating a powerful industrial impression, as much as a color scheme can. It's easy on the eye, the syntax highlights are well distinguishable, and is readable even when you switch back and forth between the editor and a white-background website. All while preserving the monotonous grayish touch.

### Supported languages

Assembly, Bash, Batch, C, C++, C#, CSS, HTML, INI, Java, JavaScript, Lua, Markdown\*, PHP, Python, Ruby, SQL, XML, YAML  
Everything else is usable but not arranged.  
If the theme gets somewhat popular, I'll optimize more languages. (Especially on request of course.)

> \* For Markdown, read the *Setting up Markdown* section at the bottom of this page.

# Installation

1. **Click** [`HERE`](https://github.com/benelaci/NPP-Industrial-Whir-Theme/archive/refs/heads/main.zip) to download all files in zip.
2. Go to **%APPDATA%\Notepad++**.
3. Open **themes** folder, or create a new folder named **themes** if it doesn't exists.
4. Install the xml in any of the following ways:
   - Copy the **.xml** file in the downloaded zip into the folder. Or
   - Import it to Notepad++ by going to *Menu -> Settings -> Import -> Import Style theme(s)*.
5. Restart Notepad++.
6. Open *Settings -> Style Configurator*.
7. Select theme **Industrial Whir** from the theme drop-down box.
8. Click **Save & Close**.

# Font

To fully achieve the desired effect, the recommended font is **JetBrains Mono**.

Install the font files in the *fonts* folder in any of the following ways:
   - open **Font Settings** (Press `Win` key, and start typing *"font"*) and drag all 2 font files at once.
   - launch the font files one by one, and click **Install**.

## Ligatures

JetBrains Mono uses ligatures, if you want those, enable DirectWrite. (*Settings* -> *Misc* -> [x] *use DirectWrite*)

![direct write on](https://i.ibb.co/hgvbD7n/direct-Write.png)

# Setting up Markdown

In the downloaded zip there is a Markdown directory. Copy `markdown.industrial whir.udl.xml` to `%AppData%\Notepad++\userDefineLangs`

By default, if you open a Markdown file in NPP, the colors may be messed up, because another Markdown UDL is arbitrarily used instead of `Markdown (Industrial Whir)`, and you have to select the correct UDL in the *Language* menu every time you open a .md file. As this practice is intolerable, it's worth putting a little work into avoiding it:

Open **all** Markdown UDLs in the `userDefineLangs` directory for editing, **except** `markdown.Industrial Whir.udl.xml`. There you can see the following code:

```
<NotepadPlus>
    <UserLang name="Markdown (Theme Name)" ext="md markdown" udlVersion="2.1">
```

Replace `ext="md markdown"` to `ext=""` in all opened documents.

This way the Industrial Whir UDL will be the only relevant one to be associated with Markdown.

# Author / contact

Laci Bene · laci.bene![|](https://i.ibb.co/7WLcqb3/ch1.gif)mail![|](https://i.ibb.co/R45zkLX/ch2.gif)ee
