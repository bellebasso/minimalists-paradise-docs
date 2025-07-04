---
{"dg-publish":true,"permalink":"/Features/Tabbed Callouts/"}
---

Create callouts with tabs for better navigation (inspired by and adpated from [this snippet](https://github.com/r-u-s-h-i-k-e-s-h/Obsidian-CSS-Snippets/blob/Collection/Snippets/Callout%20styling%20-%20Tabbed%20callout.md)).

> This is integrated to use the theme colors. If you prefer to use the original snippet, disable the tabbed callout section via the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.
# How to use?
Most markdown format supported by obsidian is supported. Any bugs feel free to open an [issue](https://github.com/bellebasso/Minimalists-Paradise/issues).
```markdown
> [!tabbed]
>
> <label>First<input type="radio" name="test" />l</label>
>
> > Lorem, ipsum dolor sit amet consectetur, adipisicing elit. (First)
> > [[Obsidian CSS|Internal Link]] > > **bold** _italic_
>
> <label>Second<input type="radio" name="test" /></label>
>
> > Lorem, ipsum dolor sit amet consectetur, adipisicing elit. (Second)
> > [External Link](https://google.com) > > $\LaTeX$
>
> <label>Third<input type="radio" name="test" />l</label>
>
> > Lorem, ipsum dolor sit amet consectetur, adipisicing elit. (Third)
> >
> > - bullet item
> > - [ ] checkbox
> > - [x] #tag
```
![tabbed callout dark 1.png](/img/user/attachments/tabbed%20callout%20dark%201.png)![tabbed callout light 1.png](/img/user/attachments/tabbed%20callout%20light%201.png)
# Style Settings Preview
![Screenshot 2025-07-04 at 01.06.07.png](/img/user/system/attachments/Screenshot%202025-07-04%20at%2001.06.07.png)