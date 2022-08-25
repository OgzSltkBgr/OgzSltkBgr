       <!-- markdownlint-disable MD033 MD041-->
<p align="center">
  <h3 align="center">⌨️ Readme Typing SVG</h3>
</p>

<p align="center">
  [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=C4F77D&background=2C162F00&width=435&lines=QA+O%C4%9Fuz+Saltuk+Bu%C4%9Fra+TOKLUCU)](https://git.io/typing-svg)
</p>

<p align="center">
  <a href="https://github.com/search?q=extension%3Amd+%22readme+typing+svg+herokuapp%22&type=Code" alt="Users" title="Repo users">
    <img src="https://freshidea.com/jonah/app/github-search-results/readme-typing-svg/index.php"/></a>
  <a href="https://discord.gg/fPrdqh3Zfu" alt="Discord" title="Dev Pro Tips Discussion & Support Server">
    <img src="https://img.shields.io/discord/819650821314052106?color=7289DA&logo=discord&logoColor=white&style=for-the-badge"/></a>
</p>
<!-- markdownlint-enable MD033 -->

## ⚡ Quick setup

1. Copy-paste the markdown below into your GitHub profile README
2. Replace the value after `?lines=` with your text. Separate lines of text with semicolons and use `+` or `%20` for spaces.
3. (Optional) Adjust the width parameter (see below) to fit the full width of your text.

```md
[![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=First+line+of+text;Second+line+of+text)](https://git.io/typing-svg)
```

## ⚙ Demo site

Here you can easily customize your Typing SVG with a live preview.

<https://readme-typing-svg.herokuapp.com/demo/>

[![Demo Site](https://user-images.githubusercontent.com/20955511/183703055-42ec8754-d84c-414f-8132-a02974224aa1.gif "Demo Site")](https://readme-typing-svg.herokuapp.com/demo/)

## 🚀 Example usage

Below are links to profiles where you can see Readme Typing SVGs in action!




## 🔧 Options

|  Parameter   |                                   Details                                   |  Type   |               Example               |
| :----------: | :-------------------------------------------------------------------------: | :-----: | :---------------------------------: |
|   `lines`    |       Text to display with lines separated by `;` and `+` for spaces        | string  | `First+line;Second+line;Third+line` |
|   `height`   |             Height of the output SVG in pixels (default: `50`)              | integer |         Any positive number         |
|   `width`    |             Width of the output SVG in pixels (default: `400`)              | integer |         Any positive number         |
|    `size`    |                     Font size in pixels (default: `20`)                     | integer |         Any positive number         |
|    `font`    |                     Font family (default: `monospace`)                      | string  |     Any font from Google Fonts      |
|   `color`    |                    Color of the text (default: `36BCF7`)                    | string  |  Hex code without # (eg. `F724A9`)  |
| `background` |             Background color of the text (default: `00000000`)              | string  |  Hex code without # (eg. `FEFF4C`)  |
|   `center`   |    `true` to center text or `false` for left aligned (default: `false`)     | boolean |          `true` or `false`          |
|  `vCenter`   |  `true` to center vertically or `false`(default) to align above the center  | boolean |          `true` or `false`          |
| `multiline`  |  `true` to wrap lines or `false` to retype on one line (default: `false`)   | boolean |          `true` or `false`          |
|  `duration`  | Duration of the printing of a single line in milliseconds (default: `5000`) | integer |         Any positive number         |
|   `pause`    |     Duration of the pause between lines in milliseconds (default: `0`)      | integer |       Any non-negative number       |

## 📤 Deploying it on your own

If you can, it is preferable to host the files on your own server.

Doing this can lead to better uptime and more control over customization (you can modify the code for your usage).

You can deploy the PHP files on any website server with PHP installed or as a Heroku app.

### Step-by-step instructions for deploying to Heroku

1. Sign in to **Heroku** or create a new account at <https://heroku.com>
2. Click the "Deploy to Heroku" button below

[![Deploy](https://www.herokucdn.com/deploy/button.svg "Deploy to Heroku")](https://heroku.com/deploy?template=https://github.com/DenverCoder1/readme-typing-svg/tree/main)

3. On the page that comes up, click **"Deploy App"** at the end of the form
4. Once the app is deployed, click **"Manage App"** to go to the dashboard
5. Scroll down to the **Domains** section in the settings to find the URL you will use in place of `readme-typing-svg.herokuapp.com`
6. [Optional] To use Google fonts or other custom fonts, you will need to configure the database. The login credentials for the database can be found by clicking the PostgreSQL add-on and going to Settings. The following is the definition for the `fonts` table that needs to be created.

```sql
CREATE TABLE fonts (
	"family" varchar(50) NOT NULL,
	css varchar(1200000) NOT NULL,
	fetch_date date NOT NULL,
	CONSTRAINT fonts_pkey PRIMARY KEY (family)
);
```

## 🤗 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have a way to improve this project.

Make sure your request is meaningful and you have tested the app locally before submitting a pull request.

### Installing requirements

#### Requirements



















<p align="left">
  <a href="https://www.youtube.com/channel/UCipSxT7a3rn81vGLw9lqRkg?sub_confirmation=1"><img alt="Youtube" title="Youtube" src="https://img.shields.io/badge/-Subscribe-red?style=for-the-badge&logo=youtube&logoColor=white"/></a>
  <a href="https://github.com/sponsors/DenverCoder1"><img alt="Sponsor with Github" title="Sponsor with Github" src="https://img.shields.io/badge/-Sponsor-ea4aaa?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>
<!-- markdownlint-enable MD033 -->

[☕ Buy me a coffee](https://ko-fi.com/jlawrence)

---



<!-- markdownlint-disable MD033 -->

<a href="https://heroku.com/"><img alt="Powered by Heroku" title="Powered by Heroku" src="https://img.shields.io/badge/-Powered%20by%20Heroku-6567a5?style=for-the-badge&logo=heroku&logoColor=white"/></a>

<!-- markdownlint-enable MD033 -->

This project uses [Twemoji](https://github.com/twitter/twemoji), published under the [CC-BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
        
       












