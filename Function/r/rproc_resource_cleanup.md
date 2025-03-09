# Function: <code>rproc_resource_cleanup</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588236256,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071588239282,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1263",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108240,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 977
    },
    {
      "addr": 18446744071589116406,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1308",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_actuate",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591618456,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589110288,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1314",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591561259,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588999712,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1330",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592681868,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589714000,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1326",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594567312,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591221632,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592959200,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1219",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592959200,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593409568,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1220",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593409568,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594155280,
      "name": "rproc_resource_cleanup",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1220",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_attach",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594155280,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501693864,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501693864,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234218992,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234218992,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295129424,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295129424,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847952,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071587850978,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```

```json
{
  "name": "rproc_resource_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_resource_cleanup",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308592,
      "name": "rproc_resource_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071588311618,
      "name": "rproc_resource_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void rproc_resource_cleanup(struct rproc * rproc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
