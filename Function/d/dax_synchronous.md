# Function: <code>dax_synchronous</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582535944,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587733694,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582636968,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587937950,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582947352,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:52",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588791022,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:52",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583021336,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:52",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588809038,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:52",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583046682,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:52",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588694878,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:52",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583384458,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:51",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589382910,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:51",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool dax_synchronous(struct dax_device * dax_dev)
```

```json
{
  "name": "dax_synchronous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589236144,
      "name": "dax_synchronous",
      "external": true,
      "loc": "drivers/dax/super.c:238",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_mmap",
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236144,
      "name": "dax_synchronous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool dax_synchronous(struct dax_device * dax_dev)
```

```json
{
  "name": "dax_synchronous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590794256,
      "name": "dax_synchronous",
      "external": true,
      "loc": "drivers/dax/super.c:283",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_mmap",
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794256,
      "name": "dax_synchronous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool dax_synchronous(struct dax_device * dax_dev)
```

```json
{
  "name": "dax_synchronous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591135760,
      "name": "dax_synchronous",
      "external": true,
      "loc": "drivers/dax/super.c:286",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_mmap",
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135760,
      "name": "dax_synchronous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool dax_synchronous(struct dax_device * dax_dev)
```

```json
{
  "name": "dax_synchronous",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591481456,
      "name": "dax_synchronous",
      "external": true,
      "loc": "drivers/dax/super.c:286",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_mmap",
        "drivers/md/dm-table.c:device_not_dax_synchronous_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481456,
      "name": "dax_synchronous",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494289100,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501176300,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
  "name": "dax_synchronous",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233684932,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288002928,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294687656,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273732690,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277880788,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605704,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587568926,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582542872,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587337006,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582595816,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587894094,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_synchronous",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582677880,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588009358,
      "name": "dax_synchronous",
      "external": false,
      "loc": "include/linux/dax.h:50",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_dax_synchronous"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool dax_synchronous(struct dax_device * dax_dev)
```
</details>
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
