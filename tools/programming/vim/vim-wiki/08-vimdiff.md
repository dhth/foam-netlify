Vimdiff
===

Resources
---
- [:fontawesome-brands-stack-overflow: How do i customize vimdiff colors](https://vi.stackexchange.com/questions/10897/how-do-i-customize-vimdiff-colors)

Custom Diff Colors
---

```vim
hi DiffAdd      gui=none    guifg=#1F2F38          guibg=#84B97C
hi DiffChange   gui=none    guifg=none             guibg=none
hi DiffDelete   gui=bold    guifg=#1F2F38          guibg=#DC657D
hi DiffText     gui=bold    guifg=#1F2F38          guibg=#D4B261
```
