# Function: <code>_opp_remove_all_static</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587537136,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:952",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587537136,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587811168,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1026",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587811168,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588016544,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016544,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874464,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1268",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874464,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588883657,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1371",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890400,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588771257,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1528",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777312,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589461769,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1538",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469408,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590939335,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1682",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590948224,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592642631,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1658",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592649456,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593073125,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1666",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593080032,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593825045,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1776",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593832240,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501273672,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501273672,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233763392,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233763392,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294796064,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294796064,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277949352,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277949352,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587641536,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641536,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587415408,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415408,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972688,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972688,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void _opp_remove_all_static(struct opp_table * opp_table)
```

```json
{
  "name": "_opp_remove_all_static",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588088064,
      "name": "_opp_remove_all_static",
      "external": true,
      "loc": "drivers/opp/core.c:1075",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_put_opp_list_kref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088064,
      "name": "_opp_remove_all_static",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void _opp_remove_all_static(struct opp_table * opp_table)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
