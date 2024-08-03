## Callouts
*Note:* You can change the callouts name next to the icon...
-> `>[!info] Here goes your text`

> [!info]
> ...

> [!note]
> ...

> [!example]
> ...

> [!bug]
> ...

> [!solved]
> ...

> [!cite]
> ...

> [!error]
> ...

> [!caution]
> ...

> [!question]
> ...

> [!check]
> ...

> [!hint]
> ...

> [!todo]
> ...

> [!summary]
> ...

> [!backlog]
> ...

> [!progress]
> ...

> [!code]
> ...

> [!review]
> ...

> [!qa]
> ...

> [!dropped]
> ...

>[!done]
> ...
### How to Customize Callouts? 

- go to `.obsidian/snippets`
- create a css file `callouts.css`
- create a new callout
```css
.callout[data-callout="new-callout-name"] { 
	--callout-color: 0, 0, 0; 
	--callout-icon: lucide-alert-circle; /* after lucide- is the thing to change*/
}
```
- icons can be found here: [Lucide](https://lucide.dev/icons/)
- HTML colors can be found here: [HTML Color Codes](https://htmlcolorcodes.com/)
- after creating custom callouts go to appearance and activate callouts css snippet