# Function: <code>clk_find_hw</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311168,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311168,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585449104,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585449104,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586166008,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166400,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586283080,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586283472,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586156856,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157248,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586658456,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658848,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587926519,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926992,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589280976,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589280976,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589577600,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589577600,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589887040,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589887040,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497738256,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497738256,
      "name": "clk_find_hw",
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230560472,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230560472,
      "name": "clk_find_hw",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275882182,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275882182,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211632,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211632,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585163840,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163840,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399504,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399504,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find_hw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506848,
      "name": "clk_find_hw",
      "external": true,
      "loc": "drivers/clk/clkdev.c:72",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:__clk_get_sys",
        "drivers/clk/clk.c:clk_core_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506848,
      "name": "clk_find_hw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct clk_hw * clk_find_hw(const char * dev_id, const char * con_id)
```
</details>
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
