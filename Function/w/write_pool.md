# Function: <code>write_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int write_pool(struct entropy_store * r, const char * buffer, size_t count)
```

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164144,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1491",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164144,
      "name": "write_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584503776,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1776",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503776,
      "name": "write_pool.constprop.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584685888,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1776",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584685888,
      "name": "write_pool.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584767392,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1804",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767392,
      "name": "write_pool.constprop.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585187488,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1803",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187488,
      "name": "write_pool.constprop.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585424144,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1895",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424144,
      "name": "write_pool.constprop.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585547248,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1920",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547248,
      "name": "write_pool.constprop.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585766624,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2001",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766624,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585909264,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909264,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586648112,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1887",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648112,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586758752,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1886",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586758752,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586639568,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1862",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586639568,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587186320,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:1884",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186320,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498733440,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498733440,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231357564,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231357564,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291888464,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291888464,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276240856,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276240856,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585670256,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670256,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585530608,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530608,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585859664,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859664,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585968048,
      "name": "write_pool",
      "external": false,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968048,
      "name": "write_pool.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int write_pool(struct entropy_store * r, const char * buffer, size_t count)
```
</details>
</li>
</ul>
