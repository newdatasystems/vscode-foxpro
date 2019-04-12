# README
## VSCode Syntax Highlighting and Snippets for Foxpro (VFP)

This extension adds generic syntax highlighting for foxpro (including function and class definition detection).

### Snippets
- *lnsel*: local select (declares a variable, stores the current area and then restores it)
- *docase*: CASE Statement (a case statement with two conditions and and otherwise)
- *prc*: PROCEDURE Declaration
- *dc*: DECLARE CLASS declaration (no external reference)
- *dco*: DECLARE CLASS declaration (using external file reference)
- *dcf*: DECLARE CLASS with direct instantiation (e.g. you can call `xxx = MyObjectFileName()` to get an instance of the object)
- *ifel*: IF/ELSE/ENDIF statement
- *ifend*: IF/ENDIF statement
- *iifs*: Simple IIF statement
- *ics*: Simple ICASE statement
- *tryc*: TRY/CATCH block
- *trycf*: TRY/CATCH/FINALLY block

### Internal Snippets
- *fs* (select), *fso* (select into object),*fin* (insert),*fup* (update),*fdel* (delete)
- *multi* - TEXTAREA based multiprompt declaration
- *mptext*,*mpname*,*mpnum*,*mpdate*,*mplist*,*mpcheck*,*mplabel*,*mprange*,*mpnote*
- *open* (this.Open),*dopen* (this.Dao.Open)
- *dw* (.Where), *dwcomplete* (.Where full)
- *djoin* (.Join), *dfields* (.Fields), *dset* (.Set), *dsetobj* (.SetObject)
- *dinval* (.IntoValue), *dinobj* (.IntoObject), *dincurs* (.IntoCursor)

### More

The "master" branch contains snippets that reference internal development tools that you most likely aren't interested in. If that's the case, please feel free to clone the "vanilla" branch which should be free of any company-specific references.

### Credits

Extension inspiration (and syntax highlighting file) from Matt Slay: https://github.com/mattslay/Visual-FoxPro-language-template-for-Visual-Studio-Code

Fox Icon provided by: by Freepik (https://www.freepik.com/) under the Creative Commons license