# Function: <code>alloc_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581005165,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:184",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581163441,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:184",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581240455,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:184",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581287826,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:183",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581427474,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:182",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581585704,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:194",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581671640,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:198",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:sget_userns"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786048,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:199",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786048,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858320,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858320,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083440,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083440,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129712,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129712,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154496,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154496,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471376,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471376,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582992512,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:199",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992512,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553936,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:199",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553936,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583770416,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:199",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770416,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977680,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:314",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977680,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493327544,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493327544,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226926864,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226926864,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286873376,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286873376,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273059718,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273059718,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827056,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827056,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764720,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764720,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818368,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818368,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
```

```json
{
  "name": "alloc_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890400,
      "name": "alloc_super",
      "external": false,
      "loc": "fs/super.c:200",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:sget",
        "fs/super.c:sget_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890400,
      "name": "alloc_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
struct super_block * alloc_super(struct file_system_type * type, int flags, struct user_namespace * user_ns)
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
