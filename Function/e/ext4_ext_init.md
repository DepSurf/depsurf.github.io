# Function: <code>ext4_ext_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_init",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759584,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3074",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954176,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3074",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044304,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581906976,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3075",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906976,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582057168,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3075",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057168,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245216,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3069",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245216,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582344336,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3131",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344336,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514752,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3151",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514752,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614848,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614848,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582926256,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3034",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926256,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582998112,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3033",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998112,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583023504,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3036",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023504,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583360256,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3074",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360256,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583871264,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3073",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871264,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584495536,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3078",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495536,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584724128,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3078",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724128,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584957120,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3054",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957120,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494264568,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494264568,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227697280,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227697280,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287972912,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287972912,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273713186,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273713186,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583584,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583584,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582520752,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520752,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573696,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573696,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655040,
      "name": "ext4_ext_init",
      "external": true,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655040,
      "name": "ext4_ext_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void ext4_ext_init(struct super_block * sb)
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
