# Function: <code>nd_label_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584737728,
      "name": "nd_label_copy",
      "external": true,
      "loc": "drivers/nvdimm/label.c:192",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:__blk_label_update"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:__blk_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737728,
      "name": "nd_label_copy.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584740640,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585095416,
      "name": "nd_label_copy",
      "external": true,
      "loc": "drivers/nvdimm/label.c:192",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090096,
      "name": "nd_label_copy.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071585092944,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585283219,
      "name": "nd_label_copy",
      "external": true,
      "loc": "drivers/nvdimm/label.c:192",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277696,
      "name": "nd_label_copy.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071585280528,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585369485,
      "name": "nd_label_copy",
      "external": true,
      "loc": "drivers/nvdimm/label.c:242",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362928,
      "name": "nd_label_copy.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071585365792,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585797338,
      "name": "nd_label_copy",
      "external": true,
      "loc": "drivers/nvdimm/label.c:244",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791360,
      "name": "nd_label_copy.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585793568,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586044974,
      "name": "nd_label_copy",
      "external": true,
      "loc": "drivers/nvdimm/label.c:253",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037856,
      "name": "nd_label_copy.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586040096,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586185102,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:261",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177104,
      "name": "nd_label_copy.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586421838,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586415088,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586568606,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586561728,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587346096,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346096,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587407632,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407632,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587289568,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289568,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587856336,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856336,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589207664,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:263",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207664,
      "name": "nd_label_copy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590763152,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:263",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590763152,
      "name": "nd_label_copy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591104592,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:263",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591104592,
      "name": "nd_label_copy",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591449872,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:263",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591449872,
      "name": "nd_label_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499458276,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499451280,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292721084,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292710576,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276680260,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586259086,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586252208,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586077454,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070576,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586516574,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586509696,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "nd_label_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586628318,
      "name": "nd_label_copy",
      "external": false,
      "loc": "drivers/nvdimm/label.c:255",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621440,
      "name": "nd_label_copy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void nd_label_copy(struct nvdimm_drvdata * ndd, struct nd_namespace_index * dst, struct nd_namespace_index * src)
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
