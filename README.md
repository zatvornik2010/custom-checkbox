custom-checkbox
===============

Creates custom view for standard html checkbox or radio input 

It is very easy to initialize plugin: ``` $("input[type='checkbox']").tiCheckbox();```

By default check button has left positioning and plugin looks for label near standard input  

You should put custom input and its label into one parent container, for example:
```html
    <p><input type="checkbox" class="custom" checked><label>Custom checkbox</label></p>
```

If you don't want label near input to be clicked, you should set option label = "false":
```html
    $("input[type='checkbox']").tiCheckbox({label: "false"});
```

You can disable your input by adding "disable" attribute.

You can set left or right position for check icon and set margin.
```html
    $("input[type='checkbox']").tiCheckbox({
        float: "right",
        margin: "5"
    });
```

After changing your input you should to refresh custom label state:
```html
    $("input[type='checkbox']").tiCheckbox().refresh();
```

You can use this plugin also for radio inputs and groups. Plugin adds special class "radio" for
custom label container.

View examples there http://devserver.ti.dn.ua/~artem/mysamples/custom-checkbox/
