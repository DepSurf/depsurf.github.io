# Function: <code>iomap_swapfile_activate</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055248,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap.c:1378",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055248,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149344,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap.c:2093",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149344,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311920,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311920,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410976,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410976,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704704,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:135",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704704,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:135",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591345022,
      "name": "iomap_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582775984,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:140",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591287819,
      "name": "iomap_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582804224,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:142",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592246254,
      "name": "iomap_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583133104,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:142",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594026990,
      "name": "iomap_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583622112,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226432,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:142",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226432,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455872,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:142",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455872,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679040,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:142",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_swap_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679040,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494014728,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494014728,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227480772,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227480772,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287665888,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287665888,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273525282,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273525282,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379712,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379712,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317408,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317408,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370192,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370192,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449920,
      "name": "iomap_swapfile_activate",
      "external": true,
      "loc": "fs/iomap/swapfile.c:134",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449920,
      "name": "iomap_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int iomap_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * pagespan, const struct iomap_ops * ops)
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
