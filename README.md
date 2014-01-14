# Micro Grid (LESS)

---

### A lightweight CSS grid system weighing only 569 bytes!

Based on Bootstraps grid but striped down with less code and does not use their negative margins on rows, but instead applies margin between all columns excluding the first column which sits against the edge of the row like nature intended.  Use LESS to easily set the column number, and size gutters and containers using (px, %, and ems) to aid in flexible/smarter responsive designs. Breakpoints are not included so you are free to set your own to match your sites specific content needs instead of relying on a heavy framework to dictate your media query breakpoints for you. Power to the developer with Micro Grid.

### Contents

| file                    | details                                           |
|-------------------------|---------------------------------------------------|
| /index.html             | Demo & Markup                                     |
| /css/micro.grid.css     | Development CSS file                              |
| /css/micro.grid.min.css | Minified Production CSS file < 569 bytes</strong> |
| /less/micro.grid.less   | Customizable LESS Development  file               |
| /less/vars.less         | LESS Variables  file</strong>                     |
| /less/mixins.less       | LESS Mixins file</strong>                         |
| /less/build.less        | LESS Build file</strong>                          |

### Usage

#### To use the grid as-is

1. Download the ZIP or clone this repo.
2. Include ```<link rel="stylesheet" href="/css/micro.grid.min.css">``` in your HTML files.
3. Build a grid:

```
<div class="container">
    <div class="row">
      <div class="span4">hello</div>
      <div class="span4">you</div>
      <div class="span4">world</div>
    </div>
  </div>
```

#### To Customize The Grid

1. Download and install [LESS](http://lesscss.org/) or use npm from terminal: $```npm install -g less```
2. Download the ZIP or clone this repo.
3. Open /less/vars.less to set grid number (12 default), gutter width (%,em,px)(default 2%), and row width (default 100%) (row measurement must match the gutter measurement type %,em,px).
4. Compile to css using command ```lessc styles.less styles.css``` or setup autocompile using [less.app](http://incident57.com/less/)

#### To Contribute

Submit pull requests to this repo [https://github.com/jongrover/micro-grid](https://github.com/jongrover/micro-grid). Thanks

#### License

Maintained under the WTHYWTD License (Whatever The Heck You Want To Do License)

---

Built at [The Flatiron School](http://flatironschool.com/)
by Jonathan Grover
email: hello@jonathangrover.com
twitter: @jongrover
