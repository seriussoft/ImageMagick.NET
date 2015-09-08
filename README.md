<!---
# ImageMagick.NET
A wrapper around the popular ImageMagick (C/C++) codebase that allows you to safely run the same image operations but with the comfort of .NET exception control to provide more stability where possible to your .NET applications (web/console/desktop) that consume ImageMagick.
-->

# ImageMagick.NET

This is a backup of some open source work involving extending a .NET derivative of ImageMagick several years ago. Because the place I originally hosted my wrapper work is gone, I am hosting here.

_**Do note that this is in no way, shape, or form solely by me or something I created from scratch.**_
I'll include information on where to look for the original source as well as some current places to look if my work is too out of date or you want to start your own. 
_Also note that this uses the Apache 2.0 license to match the current ImageMagick .NET wrapper_

<i><b>Please also note, that the only thing I can "put my name on" is the highest level of abstraction and even then, I may not be able to claim ALL of the highest level of abstraction.</b></i> My primary purpose of this, back in the day, was to allow a site or application to not crash with unhandled exceptions that occurred outside of the .NET domain. Generally, when wrapping around unmanaged code bases, your errors will either not be transformed into exceptions you can handle, not have exceptions at all (error codes at best) or just completely exit out of the current executing domain killing your hosting application w/o anything so much as an error code.

I cannot recall if it was found off of a page from [Code Project](http://www.codeproject.com), [CodePlex](http://codeplex.com), [C-Sharp Corner](http://www.c-sharpcorner.com/), or [Dani Web Forums](http://www.daniweb.com/forums/forum61.html). I will update once I can find the root from which I grabbed several years ago. However, you can go to the following pages for more information about where this all started, how to use it, what it is, etc:
* [ImageMagick home page](http://www.imagemagick.org/script/index.php)
* [How to extend/consume ImageMagick in your language of choice](http://www.imagemagick.org/script/api.php)
* [The original ImageMagick.NET github page](https://magick.codeplex.com/)
* [Image viewer using/extending ImageMagick](https://magickviewer.codeplex.com/)
* [Graphics packages using/extending ImageMagick](https://graphicsmagick.codeplex.com/)

I will TRY to update this as I can find time not already dedicated/reserved for other tasks (whether inside or outside of development). Just remember that we, as developers/extenders/wrappers/{insert other 'title' here} all have aspirations outside of each project: other projects, paying the bills, taking care of and interacting with loved ones (family and friends), religions, hobbies, etc etc etc...

<!---
### Welcome to GitHub Pages.
This automatic page generator is the easiest way to create beautiful pages for all of your projects. Author your page content here [using GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/), select a template crafted by a designer, and publish. After your page is generated, you can check out the new `gh-pages` branch locally. If you’re using GitHub Desktop, simply sync your repository and you’ll see the new branch.

### Designer Templates
We’ve crafted some handsome templates for you to use. Go ahead and click 'Continue to layouts' to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved.

### Creating pages manually
If you prefer to not use the automatic generator, push a branch named `gh-pages` to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.

### Authors and Contributors
You can @mention a GitHub username to generate a link to their profile. The resulting `<a>` element will link to the contributor’s GitHub Profile. For example: In 2007, Chris Wanstrath (@defunkt), PJ Hyett (@pjhyett), and Tom Preston-Werner (@mojombo) founded GitHub.

### Support or Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/pages) or [contact support](https://github.com/contact) and we’ll help you sort it out.

-->