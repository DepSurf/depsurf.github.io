# Function: <code>__kernfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581507648,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1180",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507648,
      "name": "__kernfs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693040,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1228",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693040,
      "name": "__kernfs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781120,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1179",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781120,
      "name": "__kernfs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581839691,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1189",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835984,
      "name": "__kernfs_remove.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989435,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1254",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985584,
      "name": "__kernfs_remove.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582177003,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1277",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172656,
      "name": "__kernfs_remove.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272139,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1277",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268016,
      "name": "__kernfs_remove.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582436527,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432480,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582535263,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531248,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582841231,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1282",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836752,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582913983,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1281",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909504,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582941679,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1283",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936752,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583276847,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1310",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271520,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583781043,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1342",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775456,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584399628,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1418",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393584,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584628172,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1422",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621952,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584860332,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1438",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854512,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494169708,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494162992,
      "name": "__kernfs_remove.part.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227609488,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227604332,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287854152,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287846832,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273638264,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273633146,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582503999,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499984,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441215,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437216,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582494479,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490464,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
  "name": "__kernfs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575119,
      "name": "__kernfs_remove",
      "external": false,
      "loc": "fs/kernfs/dir.c:1278",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571056,
      "name": "__kernfs_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __kernfs_remove(struct kernfs_node * kn)
```
</details>
</li>
</ul>
