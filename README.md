# MarkDown.markups

<a href="[https://github.com/Jean-Charles-Duprez/MarkDown.markups]>">Lien GitHub</a></p>

## Table of Contents
1. [MD MarkDown Texte](#MD.MARKUP-01)
2. [MD MarkDown FlashNotes](#MD.MARKUP-02)
3. [MD MarkDown Tables](#MD.MARKUP-03)
4. [MD MarkDown Zones](#MD.MARKUP-04)

<a name="MD.MARKUP-01"></a>
## 1) Affichage MarkDown d'une Image


En italique : <em>en italique</em>

```html
En italique : <em>en italique</em>
```

En gras : <strong>en gras</strong>

```js
En gras : <strong>en gras</strong>
```

Encadré : <code>encadré</code>

```js
Encadré : <code>encadré</code>
```

Un lien : <a href="http://example.com">lien</a>

```js
Un lien : <a href="http://example.com">lien</a>
```

Une Image : <img alt="Image" title="icon" src="https://wallpapercave.com/wp/nV132Vj.jpg"></img>

```js
Une Image : <img alt="Image" title="icon" src="https://wallpapercave.com/wp/nV132Vj.jpg"></img>
```

<a name="MD.MARKUP-02"></a>
## 2) Affichage MarkDown d'information spécifique 
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

<a name="MD.MARKUP-03"></a>
## 3) Affichage MarkDown de Tables

| **Left**     | **Centered**     | **Right**                  |
| :----------- | :--------------: | -------------------------: |
| This is left | Text is centered | And this is right-aligned  |
| More text    | Even more text   | And even more to the right |
| Adding Pipe  | Even \| text     | *some italic*              |

<a name="MD.MARKUP-04"></a>
## 4) Affichage Zone de Code

### HTML
```html
    <div id="app">
      <h1>Bonjour tout le monde !</h1>
      <p>Ceci est mon premier site web</p>
      <button id="clic-btn">Clique ici !</button>
    </div>
```

### BASH
```bash
    echo "# ViteProject" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/TcharlyMusic/ViteProject.git
    git push -u origin main
```

### JSON
```json
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  },
```

### JS
```js
    function GetRowColor(item)
    {
        if (item["Infos"] == 'CMD')		return '<tr style="background-color:skyblue;">';
        if (item["Infos"] == 'REC')		return '<tr style="background-color:red;">';
        if (item["Infos"] == 'ABM')		return '<tr style="background-color:gray;">';
        if (item["Genre"] == 'H')		return '<tr style="background-color:green;">';
        return '<tr>';
    }
```
