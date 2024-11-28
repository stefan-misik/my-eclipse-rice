# My Eclipse CDT Rice

Whenever I create new workspace (I usually keep one workspace per project), I
have to go through these steps to configure it to my liking.


## Plugins

 * [Vrapper](http://vrapper.sourceforge.net/home/)
 * [Relative Number Ruler](https://marketplace.eclipse.org/content/relative-line-number-ruler)
 * [Darkest Dark Theme](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle)
 * [CppUTest Test Runner](https://github.com/stefan-misik/cpputest-eclipse-test-runner/releases/latest)


## Workspace Settings
 * **General > Editors > Text Editors**: Show print margin (120),
   Show white space characters (hide leading and enclosed space, hide line feed)
 * **General > Keys**: Unbind: Paste (`Ctrl+V`) and Find (`Ctrl+F`)
 * **General > Workspace**: New text file line delimiter: Other - Unix
 * **C/C++ > Code Analysis**: Customize 'No break at end of case' to use 'fall
   through' suppression comment (that's what GCC uses with -Wextra). However
   `[[fallthrough]]` attribute is preferred for C++17 and later
 * **C/C++ > Code Style > Code Templates**: Import `code_templates.xml`
 * **C/C++ > Code Style > Formatter**: Import `my_bsd_formatter.xml`
 * **C/C++ > Editor**: Documentation tool comments <- Doxygen
 * **C/C++ > Editor > Content Assist > Advanced**: Enable 'Parsing-based
   Proposals'
 * **DevStyle > Color Theme**: Icon colors: Pastels
 * **Relative Number Ruler**: Show absolute for current line number (`>`)

