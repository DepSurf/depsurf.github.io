# Function: <code>__clk_get_sys</code>

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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311248,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
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
      "addr": 18446744071585311248,
      "name": "__clk_get_sys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585449184,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
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
      "addr": 18446744071585449184,
      "name": "__clk_get_sys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586166008,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586283080,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586156856,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586658456,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587926519,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589281503,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589578143,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589887583,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497738480,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230560644,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275882344,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211712,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
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
      "addr": 18446744071585211712,
      "name": "__clk_get_sys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585163920,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
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
      "addr": 18446744071585163920,
      "name": "__clk_get_sys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399584,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
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
      "addr": 18446744071585399584,
      "name": "__clk_get_sys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```

```json
{
  "name": "__clk_get_sys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506928,
      "name": "__clk_get_sys",
      "external": false,
      "loc": "drivers/clk/clkdev.c:86",
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
      "addr": 18446744071585506928,
      "name": "__clk_get_sys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct clk * __clk_get_sys(struct device * dev, const char * dev_id, const char * con_id)
```
</details>
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
