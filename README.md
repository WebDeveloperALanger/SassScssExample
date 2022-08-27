# SassScssExample
just a Sass/SCSS Example

## utilizing Sass/SCSS under windows OS

### setup
- download Dart Sass latest release https://github.com/sass/dart-sass/releases
- unzip it and save the `dart-sass` folder anywhere you want
- add the saved `dart-sass` folder's path to `PATH` system variable
- close all your terminal windows and open a new one

change dir to your project's sass/scss folder (e.g. SassScssExample\sass\)
```
cd C:\some-folder\SassScssExample\sass\
```
now you can run `sass` command against your sass/scss files  
```
sass style-scss-example.scss ..\css\style-from-scss.css
sass style-sass-example.sass ..\css\style-from-sass.css
```

----------------------

watch example:
```
sass --watch style-scss-example.scss ..\css\style-from-scss.css
sass --watch style-sass-example.sass ..\css\style-from-sass.css
```

## WebStorm Sass FileWatcher

https://www.jetbrains.com/help/webstorm/using-file-watchers.html

- Settings => Tools => File Watcher
- add Sass
- uncheck Track only root files

in section Tool to Run Changes:

--------------

    Program: 
    sass
    
    Arguments: 
    $FileName$:$FileDir$\..\css\$FileNameWithoutExtension$.css
    
    Output paths to refresh: 	
    $FileDir$\..\css\$FileNameWithoutExtension$.css:$FileDir$\..\css\$FileNameWithoutExtension$.css.map


## Links

How to install Sass: https://sass-lang.com/install

Learn Sass / Scss https://sass-lang.com/guide


