# Function: <code>cmdline_parse_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595125488,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:5741",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
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
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595296737,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:6362",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:cmdline_parse_movablecore"
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
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595543104,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:6401",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:cmdline_parse_movablecore"
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
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596468018,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:6696",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:cmdline_parse_movablecore"
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
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602794829,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:6709",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:cmdline_parse_movablecore"
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602967601,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:6863",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602967601,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604765684,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604765684,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604884733,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7372",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604884733,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 164
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604918660,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604918660,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609232576,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7433",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609232576,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 143
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612299573,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7579",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612299573,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 143
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614439580,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7797",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614439580,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 143
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615380639,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:8039",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615380639,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 143
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617169787,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:8225",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617169787,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627858624,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:8399",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:cmdline_parse_movablecore"
      ],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627857584,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 158
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619610304,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/mm_init.c:235",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:cmdline_parse_movablecore"
      ],
      "caller_func": [
        "mm/mm_init.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619609232,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 164
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621914560,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/mm_init.c:235",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:cmdline_parse_movablecore"
      ],
      "caller_func": [
        "mm/mm_init.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621913408,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 164
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510957208,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510957208,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302610204,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302610204,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 224
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270685084,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270685084,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 126
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604824120,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604824120,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604793181,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604793181,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604901304,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604901304,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```

```json
{
  "name": "cmdline_parse_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604922841,
      "name": "cmdline_parse_core",
      "external": false,
      "loc": "mm/page_alloc.c:7402",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604922841,
      "name": "cmdline_parse_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cmdline_parse_core(char * p, long unsigned int * core, long unsigned int * percent)
```
</details>
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
