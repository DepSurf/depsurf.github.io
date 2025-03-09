# Function: <code>rproc_coredump_cleanup</code>

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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588236781,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589109124,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1246",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114544,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114544,
      "name": "rproc_coredump_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589004384,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589004384,
      "name": "rproc_coredump_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718736,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718736,
      "name": "rproc_coredump_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591226768,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591226768,
      "name": "rproc_coredump_cleanup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592975712,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592975712,
      "name": "rproc_coredump_cleanup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593426368,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593426368,
      "name": "rproc_coredump_cleanup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594169360,
      "name": "rproc_coredump_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:26",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594169360,
      "name": "rproc_coredump_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501694328,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234219432,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295130112,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587848477,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
  "name": "rproc_coredump_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588309117,
      "name": "rproc_coredump_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
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
void rproc_coredump_cleanup(struct rproc * rproc)
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
