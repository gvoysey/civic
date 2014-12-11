1.  Install node.js from [here](http://nodejs.org)
2.  Install gitbook: `sudo npm install gitbook -g`
3.  Install [calibre](http://calibre-ebook.com/download)
  * point the calibre command-line tool to the right place: `ln -s ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin` (assuming ``/usr/local/bin` is in `$PATH` )
4.  Install [gitbook-plugin-autocover](https://github.com/GitbookIO/plugin-autocover) (optional)
  * `brew install pkg-config`
  * `brew install cairo`
  * in your shell, export `$PKG_CONFIG_PATH=/opt/X11/lib/pkgconfig`
  * `npm install canvas`
  * `npm install gitbook-plugin-autocover`
5. `gitbook pdf /path/to/civic`
