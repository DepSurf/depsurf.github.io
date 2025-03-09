# Function: <code>cgroup_ssid_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579969293,
      "name": "cgroup_ssid_enabled",
      "external": false,
      "loc": "kernel/cgroup.c:250",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:proc_cgroupstats_show",
        "kernel/cgroup.c:cgroup_subtree_control_write"
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
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580001282,
      "name": "cgroup_ssid_enabled",
      "external": false,
      "loc": "kernel/cgroup.c:259",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:proc_cgroupstats_show",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options"
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
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032546,
      "name": "cgroup_ssid_enabled",
      "external": false,
      "loc": "kernel/cgroup.c:262",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:proc_cgroupstats_show",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options"
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053258,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:222",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040992,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103605,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:227",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088512,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580162677,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:230",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147104,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580210453,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:235",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194704,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580259060,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241360,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307284,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289536,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580377076,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:233",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361072,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580364004,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:233",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347840,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614409291,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:233",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350960,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615345295,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:257",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507712,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617130452,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:258",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704000,
      "name": "cgroup_ssid_enabled",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627802633,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:265",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976960,
      "name": "cgroup_ssid_enabled",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619565561,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:266",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064944,
      "name": "cgroup_ssid_enabled",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621868393,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:268",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162320,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491559368,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491539136,
      "name": "cgroup_ssid_enabled",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225523904,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225504396,
      "name": "cgroup_ssid_enabled",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284533904,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284508048,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271973214,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271955364,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580276084,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258336,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580223588,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205872,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580267332,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249584,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
```

```json
{
  "name": "cgroup_ssid_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320804,
      "name": "cgroup_ssid_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:237",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302768,
      "name": "cgroup_ssid_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool cgroup_ssid_enabled(int ssid)
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
