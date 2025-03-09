# Function: <code>selinux_fs_info_free</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583056448,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:100",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056448,
      "name": "selinux_fs_info_free.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583170272,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:100",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170272,
      "name": "selinux_fs_info_free.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583357744,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357744,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583463760,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463760,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801488,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801488,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922832,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:98",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922832,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583949824,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949824,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584314032,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314032,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584933216,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584933216,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585644464,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644464,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874208,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:97",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874208,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586122896,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:97",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122896,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495226112,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495226112,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228604168,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228604168,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289181280,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289181280,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void selinux_fs_info_free(struct super_block * sb)
```

```json
{
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274451184,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274451184,
      "name": "selinux_fs_info_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583432496,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432496,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583369568,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369568,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416272,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416272,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "selinux_fs_info_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583512432,
      "name": "selinux_fs_info_free",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:99",
      "file": "security/selinux/selinuxfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_kill_sb",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512432,
      "name": "selinux_fs_info_free.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void selinux_fs_info_free(struct super_block * sb)
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
void selinux_fs_info_free(struct super_block * sb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void selinux_fs_info_free(struct super_block * sb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void selinux_fs_info_free(struct super_block * sb)
```
</details>
</li>
</ul>
