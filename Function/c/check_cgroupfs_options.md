# Function: <code>check_cgroupfs_options</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270928,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1005",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270928,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319984,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319984,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391088,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:981",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391088,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378144,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:986",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378144,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381056,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:992",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381056,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1013",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544688,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071592161512,
      "name": "check_cgroupfs_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1004",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743264,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071593934557,
      "name": "check_cgroupfs_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1016",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019792,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071596000123,
      "name": "check_cgroupfs_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1016",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108128,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071596518286,
      "name": "check_cgroupfs_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1015",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205936,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071597418529,
      "name": "check_cgroupfs_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491576400,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491576400,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225539640,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225539640,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284554992,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284554992,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271987032,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271987032,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288784,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288784,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236160,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236160,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280032,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280032,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int check_cgroupfs_options(struct fs_context * fc)
```

```json
{
  "name": "check_cgroupfs_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580334352,
      "name": "check_cgroupfs_options",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:987",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334352,
      "name": "check_cgroupfs_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int check_cgroupfs_options(struct fs_context * fc)
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
