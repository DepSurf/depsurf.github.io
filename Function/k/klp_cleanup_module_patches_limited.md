# Function: <code>klp_cleanup_module_patches_limited</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900128,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:852",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900128,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:912",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933936,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071579937833,
      "name": "klp_cleanup_module_patches_limited.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:912",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980992,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071579984921,
      "name": "klp_cleanup_module_patches_limited.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022016,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071580026026,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073040,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071580076979,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1139",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132000,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071580136357,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1139",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110224,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071591309492,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1138",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113936,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071591251541,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1138",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255168,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071592147078,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1135",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424336,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071593919786,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1160",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666656,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071595992230,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1188",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745760,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071596510595,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1188",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830832,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071597409468,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284191824,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284191824,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041776,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071580045715,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987088,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071579991027,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033312,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071580037251,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```

```json
{
  "name": "klp_cleanup_module_patches_limited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_cleanup_module_patches_limited",
      "external": false,
      "loc": "kernel/livepatch/core.c:1080",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084016,
      "name": "klp_cleanup_module_patches_limited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071580087955,
      "name": "klp_cleanup_module_patches_limited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void klp_cleanup_module_patches_limited(struct module * mod, struct klp_patch * limit)
```
</details>
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
