# Function: <code>n_tty_receive_char_flagged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583977488,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1472",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977488,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584309760,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1444",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584309760,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584491824,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1444",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491824,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573744,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1444",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573744,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985776,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1442",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985776,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585219520,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1460",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219520,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585338992,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1473",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338992,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585551968,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551968,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585692848,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692848,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420976,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_fast",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420976,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586536928,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1471",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_fast",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536928,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586421520,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1472",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_fast",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421520,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948544,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1440",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948544,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588244288,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1425",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244288,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656192,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1448",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656192,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589959824,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1447",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959824,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, u8 c, u8 flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590298864,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1465",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590298864,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498368544,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498368544,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231055024,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231055024,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291556416,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291556416,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276041978,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276041978,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585453872,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453872,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585323904,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323904,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585643248,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585643248,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void n_tty_receive_char_flagged(struct tty_struct * tty, unsigned char c, char flag)
```

```json
{
  "name": "n_tty_receive_char_flagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585751376,
      "name": "n_tty_receive_char_flagged",
      "external": false,
      "loc": "drivers/tty/n_tty.c:1475",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751376,
      "name": "n_tty_receive_char_flagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char c</code> ➡️ <code>u8 c</code>
</li>
<li>
<b>Param type changed. </b>
<code>char flag</code> ➡️ <code>u8 flag</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
