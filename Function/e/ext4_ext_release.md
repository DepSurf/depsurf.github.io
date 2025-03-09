# Function: <code>ext4_ext_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581759600,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3083",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759600,
      "name": "ext4_ext_release",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581954192,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3105",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954192,
      "name": "ext4_ext_release",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582044320,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3105",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044320,
      "name": "ext4_ext_release",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3106",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906992,
      "name": "ext4_ext_release",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3106",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057184,
      "name": "ext4_ext_release",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3100",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245232,
      "name": "ext4_ext_release",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3162",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344352,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514768,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3182",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514768,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614864,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614864,
      "name": "ext4_ext_release",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3065",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926272,
      "name": "ext4_ext_release",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3064",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998128,
      "name": "ext4_ext_release",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3067",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023520,
      "name": "ext4_ext_release",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3105",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360272,
      "name": "ext4_ext_release",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3104",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871280,
      "name": "ext4_ext_release",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3109",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495568,
      "name": "ext4_ext_release",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3109",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724160,
      "name": "ext4_ext_release",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3085",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957152,
      "name": "ext4_ext_release",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494264592,
      "name": "ext4_ext_release",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227697304,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287972928,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287972928,
      "name": "ext4_ext_release",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273713212,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583600,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583600,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582520768,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520768,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573712,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573712,
      "name": "ext4_ext_release",
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
void ext4_ext_release(struct super_block * sb)
```

```json
{
  "name": "ext4_ext_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655056,
      "name": "ext4_ext_release",
      "external": true,
      "loc": "fs/ext4/extents.c:3228",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655056,
      "name": "ext4_ext_release",
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
