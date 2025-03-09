# Function: <code>badblocks_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585725728,
      "name": "badblocks_show",
      "external": false,
      "loc": "drivers/md/md.c:8913",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725728,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117184,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:450",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117184,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229104,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:475",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229104,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283120,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:475",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283120,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463360,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:475",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463360,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675952,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:475",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675952,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783232,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:475",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783232,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972992,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972992,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076352,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076352,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466608,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466608,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581632,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581632,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613712,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613712,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592315524,
      "name": "badblocks_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585028208,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:465",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099949,
      "name": "badblocks_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071585745216,
      "name": "badblocks_show",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:465",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596108127,
      "name": "badblocks_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071586526368,
      "name": "badblocks_show",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:465",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596632031,
      "name": "badblocks_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071586772576,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:1497",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597538486,
      "name": "badblocks_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071587044800,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495916368,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495916368,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229261816,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229261816,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290129472,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290129472,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275031048,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275031048,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584045088,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584045088,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980848,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980848,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028848,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028848,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
ssize_t badblocks_show(struct badblocks * bb, char * page, int unack)
```

```json
{
  "name": "badblocks_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131344,
      "name": "badblocks_show",
      "external": true,
      "loc": "block/badblocks.c:467",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/md/md.c:ubb_show",
        "drivers/md/md.c:bb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131344,
      "name": "badblocks_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
