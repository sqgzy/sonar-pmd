# TooManyStaticImports
**Category:** `pmd`<br/>
**Rule Key:** `pmd:TooManyStaticImports`<br/>


-----

If you overuse the static import feature, it can make your program unreadable and  unmaintainable, polluting its namespace with all the static members you import. Readers of your code (including you, a few months after you wrote it) will not know which class a static member comes from (Sun 1.5 Language Guide).
