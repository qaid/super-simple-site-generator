# Making A Basic Simple Site Generator

## To fully grok Gulp, Bower, Node, etc and replace dependency on a dead app (Mixture)

For basic sites I’ve previously built, I used a static site generator called Mixture app, which I really enjoyed using. Convenience is obvious, but it also had some features that I really liked and found them to be unique. Anyway, the app’s support has long since ended, so I don’t think it makes sense to continue using the product. There are plenty of static site generators out there: metalsmith, jekyll, on and on. Instead of using something someone else built, I thought I’d take the opportunity to build my own thing that suits my own needs for my specific use case. Since it would be a learning experience while I explore and implement things like Node, Bower, and Gulp, And write about it.

My first step is to write about it. I’ve listed the things that the Mixture app does (and that I value) and then some things that it didn’t do or that it did less than perfectly.

### Mixture does:
- Live preview (BrowserSync?)
- Responsive and multi-device preview (BrowserSync?)
- Sass processor (use PostCSS?)
- Concat and minification
- image optimization
- export to dist/public folder for web
- publish to gh-pages branch and push
- Template system
- Configuration file for options
- Data file (JSON) as model / source of rendering in template at run-time

### Improving on Mixture
- use Gulp for processing all the parts
- some kind of automated testing support
- frameworks choices / one that is implemented
- choice of template systems
- UI for managing config options
- Speed (Mixture was frequently molasses - I think it was their Ruby version of Sass processing)
----
Testing prose.io