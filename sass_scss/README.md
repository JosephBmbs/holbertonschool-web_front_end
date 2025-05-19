<h1 align="center">🎨 SASS & SCSS Project</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/babakness/sass-module-types/master/.github/images/animation.gif" alt="SASS GIF" />
</p>

## 📚 Resources

- [Sass Basics](https://sass-lang.com/guide)
- [Sass flow control directives: @if, @for, @each and @while](https://sass-lang.com/documentation/at-rules/control/)
- [Sass references](https://sass-lang.com/documentation/)

## 🎯 Learning Objectives

By the end of this project, you should be able to explain the following without using Google:

### General

- What Sass means
- How to write Sass & SCSS files
- The difference between Sass and SCSS
- What is Sass preprocessing
- How to declare a variable
- How to use nested definitions
- How to import a Sass file
- How to use mixins
- How to declare extend/inheritance styles
- How to manipulate operators

## ✅ Requirements

### General

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be executed on **Ubuntu 20.04 LTS** using **Sass 1.82.0** (or higher)
- All your files must end with a new line
- All your SCSS files should have a comment at the beginning (i.e. syntax below)
- All your files must start with a comment describing the task
- A `README.md` file is mandatory at the root of the project
- File length will be tested using `wc`

## 💬 SCSS File Comment Format

Example:

```scss
/* My style */
body {
  .container {
    color: #3D3D3D;
  }
}
```

## 🛠️ Installing Sass/SCSS on Ubuntu 20.04 LTS

```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo npm install -g npm@10
sudo npm install -g sass@^1.82.0
sass --version
# Output: 1.82.0 compiled with dart2js 3.5.4

