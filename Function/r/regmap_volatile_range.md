# Function: <code>regmap_volatile_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584504298,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:146",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_raw_read",
        "drivers/base/regmap/regmap.c:regmap_bulk_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584851369,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:147",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585044905,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:170",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585129334,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:170",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585555878,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:171",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797760,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:171",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797760,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585931008,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:203",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931008,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586172544,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586172544,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586320944,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586320944,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587095787,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587181835,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587069323,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587640427,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588984189,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590504975,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590829151,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591172207,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:200",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499156920,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499156920,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231692664,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231692664,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292354000,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292354000,
      "name": "regmap_volatile_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276457732,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276457732,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586084192,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586084192,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585930144,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930144,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268912,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268912,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```

```json
{
  "name": "regmap_volatile_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380016,
      "name": "regmap_volatile_range",
      "external": false,
      "loc": "drivers/base/regmap/regmap.c:199",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:regmap_raw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380016,
      "name": "regmap_volatile_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
```
</details>
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
bool regmap_volatile_range(struct regmap * map, unsigned int reg, size_t num)
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
