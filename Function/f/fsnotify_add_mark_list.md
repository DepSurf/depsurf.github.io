# Function: <code>fsnotify_add_mark_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct hlist_head * head, struct fsnotify_mark * mark, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271824,
      "name": "fsnotify_add_mark_list",
      "external": true,
      "loc": "fs/notify/mark.c:299",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271824,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int fsnotify_add_mark_list(struct hlist_head * head, struct fsnotify_mark * mark, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437328,
      "name": "fsnotify_add_mark_list",
      "external": true,
      "loc": "fs/notify/mark.c:321",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437328,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int fsnotify_add_mark_list(struct hlist_head * head, struct fsnotify_mark * mark, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518272,
      "name": "fsnotify_add_mark_list",
      "external": true,
      "loc": "fs/notify/mark.c:321",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518272,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581571982,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:504",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581716286,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:501",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581883243,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:507",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581968221,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:547",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099584,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
    },
    {
      "addr": 18446744071582102807,
      "name": "fsnotify_add_mark_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582178631,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:547",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413936,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
    },
    {
      "addr": 18446744071582417342,
      "name": "fsnotify_add_mark_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:547",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468048,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
    },
    {
      "addr": 18446744071591340930,
      "name": "fsnotify_add_mark_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:545",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495104,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
    },
    {
      "addr": 18446744071591283630,
      "name": "fsnotify_add_mark_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:574",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582809616,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
    },
    {
      "addr": 18446744071592236170,
      "name": "fsnotify_add_mark_list.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:609",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364784,
      "name": "fsnotify_add_mark_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
    },
    {
      "addr": 18446744071594016423,
      "name": "fsnotify_add_mark_list.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583948624,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:609",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948624,
      "name": "fsnotify_add_mark_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171904,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:609",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171904,
      "name": "fsnotify_add_mark_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584386128,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:601",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386128,
      "name": "fsnotify_add_mark_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493733800,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493733800,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227258728,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227258728,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287343456,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287343456,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
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
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273342670,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273342670,
      "name": "fsnotify_add_mark_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582147367,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582084807,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582137847,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_add_mark_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582210853,
      "name": "fsnotify_add_mark_list",
      "external": false,
      "loc": "fs/notify/mark.c:543",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int fsnotify_add_mark_list(struct hlist_head * head, struct fsnotify_mark * mark, int allow_dups)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```
</details>
</li>
</ul>
