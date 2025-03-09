# Function: <code>rproc_prepare_subdevices</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588237988,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1093",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589114070,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1104",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591615661,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1162",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615661,
      "name": "rproc_prepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591558749,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1168",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558749,
      "name": "rproc_prepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592679359,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1184",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679359,
      "name": "rproc_prepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594564744,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1180",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564744,
      "name": "rproc_prepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592958384,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1073",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592958384,
      "name": "rproc_prepare_subdevices",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593408752,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1074",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593408752,
      "name": "rproc_prepare_subdevices",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594154464,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1074",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594154464,
      "name": "rproc_prepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501695824,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1093",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234220696,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1093",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295131916,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1093",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587849684,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1093",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_prepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588310324,
      "name": "rproc_prepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1093",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int rproc_prepare_subdevices(struct rproc * rproc)
```
</details>
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
