# Bookie: An ebook publishing toolchain written mostly in Ruby

While I have not looked especially far and wide, I haven't found a book
publishing toolchain that I like which both has a nice workflow AND does not
rely on a ton of heavyweight dependencies. Since I have a real need for
outputting nice documents in PDF, ePUB, and MOBI format, I am going to
experiment with building a tool that fits my personal tastes and workflow.

## Roadmap

My initial goal is just to mess around with parsing a tiny subset of Markdown
into Ruby objects. Once I've got that far, I'll work on a proof of concept PDF
outputter, probably using [Prawn](http://prawn.majesticseacreature.com). If I 
make it that far without discovering some obviously better tool or deciding 
that this is going to be a huge time sink, I'll re-visit this document and
put together a proper release plan.

## Dependencies

Bookie targets Ruby 1.9.2 exclusively, and will not run on Ruby 1.8.
PDF generation is provided by [Prawn](http::/prawn.majesticseacreature.com),
ePUB from [eeepub](https://github.com/jugyo/eeepub), and MOBI via the command
line tool [kindlegen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000234621).

Prawn and eeepub are free software projects available via rubygems, kindlegen is
free-as-in-beer proprietary software from Amazon that needs to be installed 
manually.

## Contributing

I'm happy to accept contributions to this project, but probably won't
have a formal process for doing so until I've gone beyond the proof of concept
phase. Please do catch up with me if you have questions, suggestions, or ideas
though. I am @seacreature on Freenode and twitter, and my email address is 
gregory.t.brown@gmail.com.

## License

Bookie is Free Software, available under the GNU General Public License (v3).
Please see the GPLv3 file for details, and feel free to contact me if you have
any questions
