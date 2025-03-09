# Function: <code>badblocks_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115344,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:151",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115344,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227056,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:171",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227056,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1249
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281136,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:171",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281136,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1201
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583461392,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:171",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461392,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583674000,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:171",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674000,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781280,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:171",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781280,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971088,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971088,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074448,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074448,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465472,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465472,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1128
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580496,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580496,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584612624,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612624,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1076
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592315412,
      "name": "badblocks_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071585027088,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:162",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099835,
      "name": "badblocks_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071585744080,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:162",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596108249,
      "name": "badblocks_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071586526800,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:162",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596632114,
      "name": "badblocks_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586773008,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052226,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:1429",
      "file": "block/badblocks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/badblocks.c:badblocks_store"
      ],
      "caller_func": [
        "drivers/nvdimm/badrange.c:set_badblock",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052016,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495916872,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495916872,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229258972,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229258972,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1704
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290126928,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290126928,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275029366,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275029366,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584043184,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043184,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583978944,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978944,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026944,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026944,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```

```json
{
  "name": "badblocks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129440,
      "name": "badblocks_set",
      "external": true,
      "loc": "block/badblocks.c:163",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/badblocks.c:badblocks_store",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:super_1_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129440,
      "name": "badblocks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int badblocks_set(struct badblocks * bb, sector_t s, int sectors, int acknowledged)
```
</details>
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
