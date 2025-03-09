# Function: <code>set_selection_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:180",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606086,
      "name": "set_selection_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585604272,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1578
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585746928,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746928,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586479047,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:353",
      "file": "drivers/tty/vt/selection.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586478736,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586592023,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:353",
      "file": "drivers/tty/vt/selection.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591712,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586475888,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:353",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586475888,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004352,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:353",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004352,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588303200,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:353",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303200,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589720768,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:354",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720768,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590025600,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:354",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590025600,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590364224,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:354",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590364224,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498451296,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498451296,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231114836,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231114836,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291638112,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291638112,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276095356,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276095356,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507952,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507952,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585377776,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585377776,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697328,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697328,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```

```json
{
  "name": "set_selection_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805344,
      "name": "set_selection_kernel",
      "external": true,
      "loc": "drivers/tty/vt/selection.c:348",
      "file": "drivers/tty/vt/selection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/selection.c:set_selection_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805344,
      "name": "set_selection_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int set_selection_kernel(struct tiocl_selection * v, struct tty_struct * tty)
```
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
