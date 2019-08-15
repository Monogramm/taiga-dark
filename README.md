# Dark Theme theme for Taiga

:construction: **This is a work in progress and not ready for production!**

This theme aims to provide a dark theme based on the Official Taiga theme.

**References**:
* https://github.com/taigaio/taiga-front/issues/994

## Usage

Copy `taiga-dark` folder in `app/themes`, then compile `taiga-dark` theme with
```
$ gulp --theme taiga-dark
```

If you want to compile all themes you should run.
```
gulp compile-themes
```

Add `taiga-dark` theme to `dist/conf.json`
```
{
    "themes": ["taiga", "taiga-dark"]
}
```

Now you can select taiga-dark theme from your profile settings :)
