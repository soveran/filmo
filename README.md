Filmo
=====

A single page presentation tool.

Description
-----------

Filmo is an HTML document tailored for quick presentations. Check
the demo at [files.soveran.com/filmo](http://files.soveran.com/filmo).

Usage
-----

Clone this repository, then edit the file `index.html`.

Each slide is contained in a `<section>` tag.

``` html
<section class="s1">
  <p><span>This is a slide.</span></p>
</section>
```

For each slide, you need to define the background image.

``` css
section.s3 { background-image: url("3.jpg"); }
```

Finally, you need to put the images in this same folder.

## Getting Started

Get started by cloning this repository:

```
git clone https://github.com/soveran/filmo.git
```

Then edit at will.
