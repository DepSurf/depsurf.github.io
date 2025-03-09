# Function: <code>cgroup_root_from_kf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579976661,
      "name": "cgroup_root_from_kf",
      "external": false,
      "loc": "kernel/cgroup.c:1093",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup.c:cgroup_show_options"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580009218,
      "name": "cgroup_root_from_kf",
      "external": false,
      "loc": "kernel/cgroup.c:1138",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_show_options",
        "kernel/cgroup.c:cgroup_show_path"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580042802,
      "name": "cgroup_root_from_kf",
      "external": false,
      "loc": "kernel/cgroup.c:1141",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_show_options",
        "kernel/cgroup.c:cgroup_show_path"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580038226,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1034",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042112,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580086690,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1203",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091616,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580144914,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1206",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150704,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580192834,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1241",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198336,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580238996,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245216,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287172,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293440,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580354628,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1274",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364576,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580341076,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1271",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351456,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580344276,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1271",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354576,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499892,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1302",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511552,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580698711,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1305",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708080,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580970823,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981248,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581059415,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1294",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069136,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156583,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1274",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166560,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491538768,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491543520,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225503408,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225508428,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284506372,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284513504,
      "name": "cgroup_root_from_kf",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271952954,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271959112,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580255972,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262240,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580203524,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209744,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247220,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253488,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```

```json
{
  "name": "cgroup_root_from_kf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302276,
      "name": "cgroup_root_from_kf",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1282",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_show_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306816,
      "name": "cgroup_root_from_kf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct cgroup_root * cgroup_root_from_kf(struct kernfs_root * kf_root)
```
</details>
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
