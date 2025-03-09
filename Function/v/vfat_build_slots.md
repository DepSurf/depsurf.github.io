# Function: <code>vfat_build_slots</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581988108,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:578",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582201087,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:578",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582290575,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:589",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582375479,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:589",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582526256,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:578",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582717229,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:578",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582823184,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:578",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998432,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998432,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583104624,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583104624,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424336,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424336,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538208,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538208,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561344,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561344,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919904,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919904,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498816,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498816,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585165552,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585165552,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585394560,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394560,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585629440,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629440,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494812232,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494812232,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228231148,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228231148,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288652336,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288652336,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1880
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274139832,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274139832,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073360,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073360,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010512,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010512,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061968,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061968,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```

```json
{
  "name": "vfat_build_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151248,
      "name": "vfat_build_slots",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:579",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151248,
      "name": "vfat_build_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int vfat_build_slots(struct inode * dir, const unsigned char * name, int len, int is_dir, int cluster, struct timespec64 * ts, struct msdos_dir_slot * slots, int * nr_slots)
```
</details>
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
