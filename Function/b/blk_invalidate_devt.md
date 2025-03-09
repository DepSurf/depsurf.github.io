# Function: <code>blk_invalidate_devt</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583961315,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955840,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583960000,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584064797,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059312,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071584063472,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584462004,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:624",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/partitions/core.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584460096,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495907028,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495900600,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446603336495905568,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229249852,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229242624,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 3229248500,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290115448,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290107328,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 13835058055290113584,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275022010,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275016486,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446743936275020752,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584033533,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028048,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071584032208,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583969325,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963856,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583968000,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017293,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011808,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071584015968,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_invalidate_devt(dev_t devt)
```

```json
{
  "name": "blk_invalidate_devt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119863,
      "name": "blk_invalidate_devt",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": [
        "block/genhd.c:del_gendisk",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114736,
      "name": "blk_invalidate_devt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071584118528,
      "name": "blk_invalidate_devt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void blk_invalidate_devt(dev_t devt)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void blk_invalidate_devt(dev_t devt)
```
</details>
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
