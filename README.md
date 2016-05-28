<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Dev</a>
<ul>
<li><a href="#sec-1-1">1.1. Sat May 28 14:44:09 CDT 2016</a></li>
</ul>
</li>
</ul>
</div>
</div>

# Dev<a id="sec-1" name="sec-1"></a>

## Sat May 28 14:44:09 CDT 2016<a id="sec-1-1" name="sec-1-1"></a>

[Step-by-Step to Angular2 and Firebase](https://www.gitbook.com/book/rwillmer/step-by-step-to-angular2-and-firebase/details)

<https://github.com/rwillmer/ng2-firebase-step-by-step>

1.  Create my initial package.json.
    
        {
            "name": "ng2fb-tutorial",
            "version": "0.0.1",
            "author": {
                "name": "Rachel Willmer/Modified by Anderson Reinkordt",
                "email": "rachel@willmer.org/son@lincolnix.net"
            },
            "homepage": "https://github.com/son1112/ng2fb-tutorial.git",
            "repository": {
                "type": "git",
                "url": "https://github.com/son1112/ng2fb-tutorial.git"
            }
        }

2.  Add a workflow tool.
    
    <http://gulpjs.com>
    
    <https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md>
    
    -   [ ] install gulp-cli globally
        
            npm install --global gulp-cli
    
    -   [ ] install gulp in project devDependencies
        
            npm install --save-dev gulp
    
    -   [ ] create a basic gulpfile.js
        
            var gulp = require('gulp');
            
            gulp.task('default', function() {
                // place code for your default task here
            });

3.  Setup an E2E test system.
4.  Write a failing E2E test system.
    -   Is H1 header present?
    -   Does it contain "Hello World!"?
5.  Write the index.html file.
6.  Watch the test pass.
