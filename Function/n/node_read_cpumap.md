# Function: <code>node_read_cpumap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584483092,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:28",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
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
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584829044,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:28",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
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
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585022241,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:28",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
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
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585107249,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:28",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533504,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:29",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533504,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777152,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:29",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777152,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585910672,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:29",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910672,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586150336,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586150336,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586298912,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298912,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069040,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069040,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587153536,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:cpulist_show",
        "drivers/base/node.c:cpumap_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153536,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587041008,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:cpulist_show",
        "drivers/base/node.c:cpumap_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587041008,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499131804,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292322656,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292322656,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062160,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062160,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585908112,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908112,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586247808,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247808,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```

```json
{
  "name": "node_read_cpumap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586357824,
      "name": "node_read_cpumap",
      "external": false,
      "loc": "drivers/base/node.c:30",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357824,
      "name": "node_read_cpumap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t node_read_cpumap(struct device * dev, bool list, char * buf)
```
</details>
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
