# MathWorks Presentation

This is the presentation I gave on 05/01/2015 at MathWorks as part of interviewing for a front end developer position.

## Viewing

Just looking to view the presentation? click [here][io-link] to check it out.

## Developing
A basic gruntfile is included to allow making changes to the presentation and seeing the results.

[node][node] needs to be [installed][node-pm] first.
then clone this repo:
```
git clone https://github.com/nttibbetts/mathworks_presentation.git
```

install grunt-cli:
```
npm install -g grunt-cli
```

use npm to install the dependencies
```
npm install
```

finally start up a local server to view the presentation as you make changes:
```
grunt
```

## License
![CC-NC-ND][cc-img]  
`presentation.md` is [CC-NC-ND][cc] licensed.

![GPLv3][gpl-img]  
The rest of the code *except* what is under `lib/` is licensed under [GPLv3][gpl].

The dependencies under `lib/` are licensed as designated by their contributors.


[io-link]: https://nttibbetts.github.io/mathworks_presentation
[node]: http://nodejs.org/download
[node-pm]: https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager
[cc]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-img]: http://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png "CC-NC-ND"
[gpl]: http://www.gnu.org/licenses/gpl-3.0.html
[gpl-img]: http://www.gnu.org/graphics/gplv3-88x31.png "GPLv3"
