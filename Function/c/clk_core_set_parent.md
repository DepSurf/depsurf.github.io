# Function: <code>clk_core_set_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int clk_core_set_parent(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_core_set_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082528,
      "name": "clk_core_set_parent",
      "external": false,
      "loc": "drivers/clk/clk.c:1764",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_set_parent",
        "drivers/clk/clk.c:clk_set_parent",
        "drivers/clk/clk.c:clk_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082528,
      "name": "clk_core_set_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
int clk_core_set_parent(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_core_set_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586493088,
      "name": "clk_core_set_parent",
      "external": false,
      "loc": "drivers/clk/clk.c:1788",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_set_parent",
        "drivers/clk/clk.c:clk_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586493088,
      "name": "clk_core_set_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int clk_core_set_parent(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_core_set_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584299808,
      "name": "clk_core_set_parent",
      "external": false,
      "loc": "drivers/clk/clk.c:1788",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_set_parent",
        "drivers/clk/clk.c:clk_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299808,
      "name": "clk_core_set_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_set_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584379147,
      "name": "clk_core_set_parent",
      "external": false,
      "loc": "drivers/clk/clk.c:1790",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_set_parent"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378560,
      "name": "clk_core_set_parent.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_set_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584787291,
      "name": "clk_core_set_parent",
      "external": false,
      "loc": "drivers/clk/clk.c:1901",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_set_parent"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786640,
      "name": "clk_core_set_parent.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int clk_core_set_parent(struct clk_core * core, struct clk_core * parent)
```
</details>
</li>
</ul>
