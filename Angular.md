## Angular 8 & @ViewChild()

If you're using Angular 8 (you can check the package.json file to find out), you have to use @ViewChild(..., { static: false }) instead of @ViewChild(...).

This adjustment is only required when working with Angular 8 (and should only be required temporarily, until Angular 9 is released).


# Template Forms
when using in the component, the module (where the component belongs to ) shoud have NativeScriptFormsModule imported (imports). 
