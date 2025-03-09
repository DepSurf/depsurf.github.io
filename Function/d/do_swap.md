# Function: <code>do_swap</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584097280,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort",
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097280,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584219920,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219920,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625856,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:133",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625856,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744256,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:133",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744256,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584772400,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:133",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772400,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202288,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:133",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202288,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void do_swap(void * a, void * b, size_t size, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038752,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:139",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038752,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void do_swap(void * a, void * b, size_t size, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587021024,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:139",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021024,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void do_swap(void * a, void * b, size_t size, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587276064,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:139",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276064,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void do_swap(void * a, void * b, size_t size, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587564800,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:139",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587564800,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510868704,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496093208,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229420160,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229420160,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290335552,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290335552,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275162218,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275162218,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584188656,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188656,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123888,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123888,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584172416,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172416,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
```

```json
{
  "name": "do_swap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584276720,
      "name": "do_swap",
      "external": false,
      "loc": "lib/sort.c:135",
      "file": "lib/sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort_r",
        "lib/sort.c:sort_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276720,
      "name": "do_swap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void do_swap(void * a, void * b, size_t size, swap_func_t swap_func)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * priv</code>
</li>
<li>
<b>Param type changed. </b>
<code>swap_func_t swap_func</code> ➡️ <code>swap_r_func_t swap_func</code>
</li>
</ul>
</details>
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
