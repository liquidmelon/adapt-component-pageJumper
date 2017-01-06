# adapt-component-pageJumper
text component with a button that jumps you to a different page



this component was derived from adaptlearning's text component which can be found here: https://github.com/adaptlearning/adapt-contrib-text



the difference is the addition of a button which allows navigation to a different page within the course



##Screenshot

![pagejumperss](https://cloud.githubusercontent.com/assets/24887794/21715124/9b874c54-d3b7-11e6-8a19-96f4176d3dfc.png)



##Button Positioning

choose one of these positions for the button using the dropdown in the properties:
left (default), center, right

you can also position the instruction text like this:

```<span style="display:block; text-align:left">oink!</span>```

```<span style="display:block; text-align:center">oink!</span>```

```<span style="display:block; text-align:right">oink!</span>```



## Limitations

the jump-to page will replace the current page in the history. to maintain a fluid user experience, it is recommended to jump to pages only within the same submenu.
