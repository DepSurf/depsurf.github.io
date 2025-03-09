# Function: <code>parse_sid</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:606",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124000,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583163931,
      "name": "parse_sid.cold.70",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:629",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310672,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583351307,
      "name": "parse_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583415744,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583457275,
      "name": "parse_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583798363,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:580",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583916138,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:581",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583944423,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:637",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584310199,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:614",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495171608,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495171608,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228558532,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228558532,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289109280,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289109280,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274414116,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274414116,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384480,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583426011,
      "name": "parse_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321568,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583363083,
      "name": "parse_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368256,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583409787,
      "name": "parse_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```

```json
{
  "name": "parse_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:631",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463840,
      "name": "parse_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583505947,
      "name": "parse_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int parse_sid(struct super_block * sb, const char * s, u32 * sid)
```
</details>
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
