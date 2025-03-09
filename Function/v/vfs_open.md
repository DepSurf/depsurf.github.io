# Function: <code>vfs_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_open(const struct path * path, struct file * file, const struct cred * cred)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988368,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:845",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988368,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int vfs_open(const struct path * path, struct file * file, const struct cred * cred)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143200,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:845",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143200,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int vfs_open(const struct path * path, struct file * file, const struct cred * cred)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218384,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:862",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218384,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int vfs_open(const struct path * path, struct file * file, const struct cred * cred)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265312,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:862",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265312,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int vfs_open(const struct path * path, struct file * file, const struct cred * cred)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404448,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:862",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404448,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int vfs_open(const struct path * path, struct file * file, const struct cred * cred)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559264,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:904",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559264,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581639140,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:887",
      "file": "fs/open.c",
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
      "addr": 18446744071581644752,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581755786,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:907",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761488,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827994,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833696,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582049338,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:940",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054304,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582098698,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:929",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104144,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123498,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:937",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129056,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440362,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:955",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_open"
      ],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445696,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582957490,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:978",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open"
      ],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964272,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583515796,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:1010",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open"
      ],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523200,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583731250,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:1045",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open"
      ],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738528,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583932050,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:1084",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open"
      ],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/backing-file.c:backing_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940416,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493293460,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493296936,
      "name": "vfs_open",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226893516,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226900032,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286828744,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_open"
      ],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286835888,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273038076,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273041768,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796730,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802432,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581734394,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740096,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581788042,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793744,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_open(const struct path * path, struct file * file)
```

```json
{
  "name": "vfs_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581857178,
      "name": "vfs_open",
      "external": true,
      "loc": "fs/open.c:912",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862880,
      "name": "vfs_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct cred * cred</code>
</li>
</ul>
</details>
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
