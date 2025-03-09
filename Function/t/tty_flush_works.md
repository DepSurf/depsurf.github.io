# Function: <code>tty_flush_works</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583970444,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1599",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584298255,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1601",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480319,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1601",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584555399,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1369",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965920,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1387",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965920,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199440,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1405",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199440,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318144,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1417",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318144,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530960,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530960,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671840,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671840,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586404008,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1423",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586519160,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1504",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586404104,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1519",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586930888,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1511",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588225191,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1501",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589634007,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1497",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589937047,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1506",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590275591,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1504",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498342944,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498342944,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231034332,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231034332,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291526592,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291526592,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276025870,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276025870,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432864,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432864,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585302912,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302912,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585622240,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622240,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void tty_flush_works(struct tty_struct * tty)
```

```json
{
  "name": "tty_flush_works",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730560,
      "name": "tty_flush_works",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1419",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730560,
      "name": "tty_flush_works",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void tty_flush_works(struct tty_struct * tty)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tty_flush_works(struct tty_struct * tty)
```
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
