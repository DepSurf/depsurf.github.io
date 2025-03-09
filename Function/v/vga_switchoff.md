# Function: <code>vga_switchoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584354208,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:488",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354208,
      "name": "vga_switchoff.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585407548,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:625",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406752,
      "name": "vga_switchoff.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585608476,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:625",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607680,
      "name": "vga_switchoff.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int vga_switchoff(struct vga_switcheroo_client * client)
```

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585688640,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:626",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688640,
      "name": "vga_switchoff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int vga_switchoff(struct vga_switcheroo_client * client)
```

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120864,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:626",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120864,
      "name": "vga_switchoff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586372535,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:680",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371408,
      "name": "vga_switchoff.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586513717,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:685",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512624,
      "name": "vga_switchoff.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586759498,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757856,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586905258,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904320,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587717085,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587714864,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587776701,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587774480,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587655994,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653776,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588242244,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588242208,
      "name": "vga_switchoff.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071592539551,
      "name": "vga_switchoff.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589621348,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589621312,
      "name": "vga_switchoff.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071594418616,
      "name": "vga_switchoff.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591222804,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591222768,
      "name": "vga_switchoff.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071596264725,
      "name": "vga_switchoff.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591582212,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582176,
      "name": "vga_switchoff.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071596792864,
      "name": "vga_switchoff.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592313220,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313184,
      "name": "vga_switchoff.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071597715837,
      "name": "vga_switchoff.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586662362,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661424,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586530698,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586529760,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586859818,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586858880,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_switchoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586965930,
      "name": "vga_switchoff",
      "external": false,
      "loc": "drivers/gpu/vga/vga_switcheroo.c:684",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964992,
      "name": "vga_switchoff.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int vga_switchoff(struct vga_switcheroo_client * client)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int vga_switchoff(struct vga_switcheroo_client * client)
```
</details>
</li>
</ul>
