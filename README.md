# ttytable
Print table on Linux or Windows terminal

<br>

# 1. Install

```bash
pip install ttytable
```

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

<br>

# 3. Themes

- **`c.style1()`**

- **`c.style2()`**

- **`c.style3()`**

- **`c.style4()`**

- **`c.style5()`**

- **`c.style6()`**

- **`c.style7()`**

- **`c.style8()`**

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
It looks like this.


<br>








