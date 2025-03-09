# Function: <code>_perf_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580427684,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:4257",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
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
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580501044,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:4534",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
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
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580565012,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:4631",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
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
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580595220,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:4723",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
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
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580675380,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806720,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5014",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806720,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1772
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873328,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5023",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873328,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1785
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969872,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5069",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969872,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1523
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024000,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024000,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1523
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581204768,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5422",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204768,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247088,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5501",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247088,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263792,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5585",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263792,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1706
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517344,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5690",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517344,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1793
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864496,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5588",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864496,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1917
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291856,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5806",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291856,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1909
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492576,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5806",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492576,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1941
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661024,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5879",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661024,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1941
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492375848,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492375848,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1572
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226261256,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226261256,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285632368,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285632368,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2100
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272469708,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272469708,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992848,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992848,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1523
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580939040,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939040,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1523
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984048,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984048,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1523
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "_perf_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044928,
      "name": "_perf_ioctl",
      "external": false,
      "loc": "kernel/events/core.c:5164",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044928,
      "name": "_perf_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1531
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
long int _perf_ioctl(struct perf_event * event, unsigned int cmd, long unsigned int arg)
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
