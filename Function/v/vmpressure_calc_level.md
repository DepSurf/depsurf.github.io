# Function: <code>vmpressure_calc_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580944053,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:111",
      "file": "mm/vmpressure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093056,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:111",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093056,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168304,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:111",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168304,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216112,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:124",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216112,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346752,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:124",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346752,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495136,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:124",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495136,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580976,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:124",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580976,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691968,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691968,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765392,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765392,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984096,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984096,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034080,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034080,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582060288,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060288,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368256,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:120",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368256,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582866944,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:120",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866944,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414288,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:120",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414288,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634560,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:120",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634560,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583829600,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:120",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829600,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493220696,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493220696,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226850340,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226850340,
      "name": "vmpressure_calc_level",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286735008,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286735008,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272995106,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272995106,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734128,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734128,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672768,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672768,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725440,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725440,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```

```json
{
  "name": "vmpressure_calc_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793632,
      "name": "vmpressure_calc_level",
      "external": false,
      "loc": "mm/vmpressure.c:121",
      "file": "mm/vmpressure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793632,
      "name": "vmpressure_calc_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
enum vmpressure_levels vmpressure_calc_level(long unsigned int scanned, long unsigned int reclaimed)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
