# Function: <code>rproc_unprepare_subdevices</code>

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
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588232598,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1151",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rproc_unprepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589107430,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1162",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589113800,
      "name": "rproc_unprepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void rproc_unprepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589106582,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1220",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615880,
      "name": "rproc_unprepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void rproc_unprepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993632,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1226",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993632,
      "name": "rproc_unprepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void rproc_unprepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589707712,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1242",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589707712,
      "name": "rproc_unprepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void rproc_unprepare_subdevices(struct rproc * rproc)
```

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591214864,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1238",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591214864,
      "name": "rproc_unprepare_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592966993,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1131",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
        "drivers/remoteproc/remoteproc_core.c:__rproc_attach",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593417377,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1132",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
        "drivers/remoteproc/remoteproc_core.c:__rproc_attach",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594163329,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1132",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
        "drivers/remoteproc/remoteproc_core.c:__rproc_attach",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501689296,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1151",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
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
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234214692,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1151",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
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
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295121256,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1151",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
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
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587844294,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1151",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
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
  "name": "rproc_unprepare_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588304934,
      "name": "rproc_unprepare_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1151",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void rproc_unprepare_subdevices(struct rproc * rproc)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void rproc_unprepare_subdevices(struct rproc * rproc)
```
</details>
</li>
</ul>
