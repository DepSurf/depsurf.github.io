# Function: <code>vfat_create_shortname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581988531,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:313",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582201471,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:313",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582290959,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:324",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582376319,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:324",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582527060,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:326",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582717977,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:326",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:326",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821024,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1940
    },
    {
      "addr": 18446744071582827372,
      "name": "vfat_create_shortname.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996480,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
    },
    {
      "addr": 18446744071583002331,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102672,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
    },
    {
      "addr": 18446744071583108523,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422176,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2160
    },
    {
      "addr": 18446744071583427831,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583536048,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2160
    },
    {
      "addr": 18446744071591354173,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559200,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2134
    },
    {
      "addr": 18446744071591297095,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917520,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2378
    },
    {
      "addr": 18446744071592281967,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495904,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2911
    },
    {
      "addr": 18446744071594064371,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585162576,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162576,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2952
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585391584,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391584,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2959
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585626464,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626464,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2959
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494810376,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494810376,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1856
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228229056,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228229056,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2092
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288650080,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288650080,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2256
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274138166,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274138166,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1666
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071408,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
    },
    {
      "addr": 18446744071583077259,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008560,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
    },
    {
      "addr": 18446744071583014411,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060016,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
    },
    {
      "addr": 18446744071583065867,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
```

```json
{
  "name": "vfat_create_shortname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_create_shortname",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:327",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_build_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149296,
      "name": "vfat_create_shortname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
    },
    {
      "addr": 18446744071583155147,
      "name": "vfat_create_shortname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfat_create_shortname(struct inode * dir, struct nls_table * nls, wchar_t * uname, int ulen, unsigned char * name_res, unsigned char * lcase)
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
