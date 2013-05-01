custom-checkbox
===============

Creates custom view for standard html checkbox or radio input 

You should put custom input and its label into one parent container, for example:
    <p><input type="checkbox" class="custom" checked><label>Custom checkbox</label></p>

If you don't want label near input to be clicked, you should set option label = "false":
    $("input[type='checkbox']").tiCheckbox({label: "false"});

You can disable your input by adding "disable" attribute.

You can set left or right position for check icon and set margin.

After changing your input you should to refresh custom label state:
    $("input[type='checkbox']").tiCheckbox().refresh();

You can use this plugin also for radio buttons and groups. Plugin adds special class "radio" for
custom label container.
