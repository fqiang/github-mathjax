
**for** i = {l, ...,1} **do** <br>
&nbsp;&nbsp;**foreach** $p$ such that $p \leq i$ and $w_{pi} \neq 0$ **do** <br>
&nbsp;&nbsp;&nbsp;&nbsp;**if** $p\ne i$ **then** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**foreach** $j \prec i$ **do** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**if** $j=p$ **then** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$w_{pp}+=2\frac{\partial \phi_i}{\partial v_p}w_{pi}$ <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**else** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$w_{jp}+=2\frac{\partial \phi_i}{\partial v_j}w_{pi}$ <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**end** <br>
&nbsp;&nbsp;&nbsp;&nbsp;**else** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**foreach** unordered pair ${j,k}$ such that $j,k \prec i$ **do** <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$w_{jk}+=\frac{\partial \phi_i}{\partial v_k}\frac{\partial \phi_i}{\partial v_j}w_{ii}$ <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**end** <br>
&nbsp;&nbsp;&nbsp;&nbsp;**end** <br>
&nbsp;&nbsp;**end** <br>
&nbsp;&nbsp;**foreach** unordered pair ${j,k}$ such that $j,k \prec i$  <br>
&nbsp;&nbsp;&nbsp;&nbsp;$w_{jk} += \bar{v}_i \frac{\partial^2 \phi_i}{\partial v_k \partial v_j}$ <br>
&nbsp;&nbsp;**end** <br>
&nbsp;&nbsp;**foreach** $j \prec i$ **do** $\bar{v}_j+= \bar{v}_i  \frac{\partial \phi_i}{\partial v_j}$
**end** <br>
