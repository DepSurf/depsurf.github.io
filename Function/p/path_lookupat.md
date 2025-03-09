# Function: <code>path_lookupat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050304,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2123",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050304,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581207744,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207744,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282720,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2249",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282720,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332192,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2285",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332192,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472336,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2283",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472336,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581631264,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2270",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631264,
      "name": "path_lookupat.isra.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581717424,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2306",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717424,
      "name": "path_lookupat.isra.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581834960,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2304",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834960,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581907424,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907424,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140192,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2321",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140192,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187296,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2319",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187296,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208432,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2409",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208432,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527200,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2437",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527200,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583065136,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2483",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065136,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631264,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2462",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631264,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850432,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850432,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057520,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2474",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057520,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493388160,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493388160,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226981736,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226981736,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286951184,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286951184,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```

```json
{
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273103398,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273103398,
      "name": "path_lookupat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581876160,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876160,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581813760,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813760,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581867472,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867472,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
  "name": "path_lookupat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945568,
      "name": "path_lookupat",
      "external": false,
      "loc": "fs/namei.c:2297",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945568,
      "name": "path_lookupat.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int path_lookupat(struct nameidata * nd, unsigned int flags, struct path * path)
```
</details>
</li>
</ul>
