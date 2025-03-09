# Function: <code>opp_debug_create_supplies</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587062602,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:38",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587360819,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:38",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587540691,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:38",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587815483,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588020683,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void opp_debug_create_supplies(struct dev_pm_opp * opp, struct opp_table * opp_table, struct dentry * pdentry)
```

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879616,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:76",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879616,
      "name": "opp_debug_create_supplies",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void opp_debug_create_supplies(struct dev_pm_opp * opp, struct opp_table * opp_table, struct dentry * pdentry)
```

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588892560,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:76",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892560,
      "name": "opp_debug_create_supplies",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588782467,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:76",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589474707,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:76",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590953885,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:77",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592656140,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:95",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593086874,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:95",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593839274,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:95",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501283532,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233772148,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294809100,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277957246,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587645675,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587419547,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587976827,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_debug_create_supplies",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588092203,
      "name": "opp_debug_create_supplies",
      "external": false,
      "loc": "drivers/opp/debugfs.c:35",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void opp_debug_create_supplies(struct dev_pm_opp * opp, struct opp_table * opp_table, struct dentry * pdentry)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void opp_debug_create_supplies(struct dev_pm_opp * opp, struct opp_table * opp_table, struct dentry * pdentry)
```
</details>
</li>
</ul>
