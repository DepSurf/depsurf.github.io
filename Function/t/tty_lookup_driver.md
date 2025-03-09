# Function: <code>tty_lookup_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583972812,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1973",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open"
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
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584305478,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1971",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open"
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
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584487537,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1971",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open"
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
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584567946,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1753",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open_by_driver"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584974912,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1805",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974912,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585205408,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1823",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205408,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585323680,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1835",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323680,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585535568,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535568,
      "name": "tty_lookup_driver",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585676448,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676448,
      "name": "tty_lookup_driver",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586408608,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408608,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586520480,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1921",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586520480,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586404848,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1936",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404848,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586931632,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1930",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931632,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588230752,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1918",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230752,
      "name": "tty_lookup_driver",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642048,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1913",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642048,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589945696,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1922",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945696,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590283872,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1920",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590283872,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498346536,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498346536,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231038036,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231038036,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291534368,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291534368,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276029192,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276029192,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585437472,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437472,
      "name": "tty_lookup_driver",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585307520,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307520,
      "name": "tty_lookup_driver",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626848,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626848,
      "name": "tty_lookup_driver",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
```

```json
{
  "name": "tty_lookup_driver",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585738624,
      "name": "tty_lookup_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1837",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738624,
      "name": "tty_lookup_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
struct tty_driver * tty_lookup_driver(dev_t device, struct file * filp, int * index)
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
