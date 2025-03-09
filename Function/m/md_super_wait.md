# Function: <code>md_super_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585741216,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:754",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741216,
      "name": "md_super_wait.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071585757824,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153480,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:752",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change"
      ],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137264,
      "name": "md_super_wait.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071586153824,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586349040,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:779",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349040,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586449456,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:791",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449456,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586916608,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:826",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916608,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587207888,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:841",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587207888,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388224,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:834",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388224,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587659616,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:895",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587659616,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587863792,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587863792,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588714880,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:1033",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714880,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588742400,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:1022",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742400,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588627536,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:981",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_flush",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588627536,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589304912,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:982",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_flush",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304912,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590776752,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:986",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_flush",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590776752,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592457584,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:977",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_flush",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592457584,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592879904,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:953",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_flush",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592879904,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593629296,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:1065",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_flush",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593629296,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501092288,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501092288,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233608180,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233608180,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294587504,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:md_bitmap_wait_writes",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294587504,
      "name": "md_super_wait",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277817148,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277817148,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587494768,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587494768,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587262928,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262928,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587819936,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819936,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int md_super_wait(struct mddev * mddev)
```

```json
{
  "name": "md_super_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587933600,
      "name": "md_super_wait",
      "external": true,
      "loc": "drivers/md/md.c:907",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_90_rdev_size_change",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933600,
      "name": "md_super_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
