# Function: <code>rproc_coredump</code>

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
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588240747,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1565",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114427,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1616",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114427,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:230",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591619860,
      "name": "rproc_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589114656,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:234",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591563242,
      "name": "rproc_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589004496,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:234",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592683952,
      "name": "rproc_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589718848,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:234",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594569366,
      "name": "rproc_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591226880,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592975840,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:234",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592975840,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1025
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
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593426496,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:234",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593426496,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1206
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
void rproc_coredump(struct rproc * rproc)
```

```json
{
  "name": "rproc_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594172544,
      "name": "rproc_coredump",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:235",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594172544,
      "name": "rproc_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1206
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
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501697784,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1565",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
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
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234222572,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1565",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
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
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295134344,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1565",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
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
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587852443,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1565",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
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
  "name": "rproc_coredump",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588313083,
      "name": "rproc_coredump",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1565",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery"
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
void rproc_coredump(struct rproc * rproc)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
