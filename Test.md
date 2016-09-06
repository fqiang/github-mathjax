
**for** i = {l, ...,1} <br>
&nbsp;&nbsp;*\#pushing* <br>
&nbsp;&nbsp;**foreach** $p$ such that $p \leq i$ and $w_{pi} \neq 0$ **d**o <br>
&nbsp;&nbsp;&nbsp;&nbsp; **if** $p\ne i$ **then** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**foreach** $j \leq i$ **do** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**if** $j=p$ **then**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$w_{pp}+=2\frac{\partial \phi_i}{\partial v_p}w_{pi}$ <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**end** <br>
&nbsp;&nbsp;**end** <br>
