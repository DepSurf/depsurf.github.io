# Function: <code>kernfs_name_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508485,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_name",
        "fs/kernfs/dir.c:pr_cont_kernfs_name"
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
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581694091,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
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
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581782043,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832000,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832000,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981616,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:43",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981616,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169104,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:43",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169104,
      "name": "kernfs_name_locked",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264176,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:43",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264176,
      "name": "kernfs_name_locked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428688,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428688,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527440,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527440,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582832928,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832928,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905680,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905680,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933488,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933488,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268336,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268336,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583771504,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:49",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771504,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389008,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:54",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389008,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617328,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:54",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617328,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849424,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:54",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849424,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494159224,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494159224,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227600076,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227600076,
      "name": "kernfs_name_locked",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287839952,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287839952,
      "name": "kernfs_name_locked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273631306,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273631306,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496176,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496176,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433408,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433408,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486656,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486656,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_name_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567216,
      "name": "kernfs_name_locked",
      "external": false,
      "loc": "fs/kernfs/dir.c:42",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567216,
      "name": "kernfs_name_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int kernfs_name_locked(struct kernfs_node * kn, char * buf, size_t buflen)
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
