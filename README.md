# SCSS Demo

Besides from using SCSS to create more flexible design in a shorter period of time, there are several SCSS/SASS frameworks or toolkits available out there now.
In this small demo project, I'm using Susy, Breakpoint and Compass to demonstrate how easy it can be to make a responsive web design with your own flexible css grids, media queries, and everything else.

# Syntactically Awesome Style-Sheets (SASS) vs Sassy CSS (SCSS)?

SCSS builds on top of CSS was built with the purpose in mind to look closer like CSS, so that people won't have to learn new syntax. The CSS syntax is basically a subset of the SCSS syntax.
Thefore, the SCSS syntax has become more popular than the SASS syntax.

## SASS

```.test
    float: left
    width: 100%
    a
        color: rgb(100,0,100)
```

- Indentation matters
- Uses no curly braces or semi-colons

## SCSS

```
.box {
    float: left;
    width: 100%;
    a {
        color: rgb(100,0,100);
    }
}
```

- Indentation plays no role
- Uses curly braces and semi-colons to structure the code
- Syntax is closer to CSS

## Installation

To play around in your editor with the code, make sure you've got Ruby installed.

Then install the following from your CLI:

```bash
gem install susy
gem install breakpoint
gem install compass
```

## Usage

```html
Open the index.html file in your browser
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
