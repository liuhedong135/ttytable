# ttytable
Print table on Linux or Windows terminal

<br>

# 1. Install

```bash
pip install ttytable
```

<br>

> Waring: Only the following is supported
> - Xshell: Default theme
> - MobaXterm: All 
> - Vmware: All
> 
> Other tools have not been tested yet

<br>

---

<br>

# 2. Use

```python
from ttytable.table import Use
c = Use(['Name', 'Age', 'Country'])
c.add_row(['Oliven', '20', 'China'])
c.add_row(['Bob', '29', 'American'])
c.echo()

```
![use](https://github.com/liuhedong135/ttytables/blob/master/photo/use.png)

<br>

---

<br>

# 3. Themes

- **`c.style()`**<br>
![style](https://github.com/liuhedong135/ttytables/blob/master/photo/style.png)
- **`c.style1()`**<br>
![style1](https://github.com/liuhedong135/ttytables/blob/master/photo/style1.png)
- **`c.style2()`**<br>
![style2](https://github.com/liuhedong135/ttytables/blob/master/photo/style2.png)
- **`c.style3()`**<br>
![style3](https://github.com/liuhedong135/ttytables/blob/master/photo/style3.png)
- **`c.style4()`**<br>
![style4](https://github.com/liuhedong135/ttytables/blob/master/photo/style4.png)
- **`c.style5()`**<br>
![style5](https://github.com/liuhedong135/ttytables/blob/master/photo/style5.png)
- **`c.style6()`**<br>
![style6](https://github.com/liuhedong135/ttytables/blob/master/photo/style6.png)
- **`c.style7()`**<br>
![style7](https://github.com/liuhedong135/ttytables/blob/master/photo/style7.png)
- **`c.style8()`**<br>
![style8](https://github.com/liuhedong135/ttytables/blob/master/photo/style8.png)
<br>

## 3.1 Custom
You can customize it.
```python
c.top_left = '1'     # ↖
c.top_up = '2'       # ↑
c.top_right = '3'    # ↗
c.left = '4'         # ←
c.center = '5'       # ·
c.right = '6'        # →
c.bottom_left = '7'  # ↙
c.bottom_down = '8'  # ↓
c.bottom_right = '9' # ↘
c.vertical = 'o'     # |
c.across = 'x'       # -
c.echo()
```
It looks like this.<br>
![custom](https://github.com/liuhedong135/ttytables/blob/master/photo/custom.png)

<br>








