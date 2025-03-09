# Function: <code>userfaultfd_ctx_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581314193,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:117",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581481034,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:117",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581561704,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:124",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581610688,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:142",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610688,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581754960,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:139",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754960,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581923200,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:141",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923200,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007072,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:141",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007072,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582143632,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143632,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582220832,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220832,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582466022,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582523362,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582552144,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:152",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582868293,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:153",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583424281,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:155",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584012656,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:171",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584237952,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:201",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584461936,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:205",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493790964,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227302636,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287411048,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273383784,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189568,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189568,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127088,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127088,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180048,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180048,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```

```json
{
  "name": "userfaultfd_ctx_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256080,
      "name": "userfaultfd_ctx_get",
      "external": false,
      "loc": "fs/userfaultfd.c:151",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_prep",
        "fs/userfaultfd.c:dup_userfaultfd",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256080,
      "name": "userfaultfd_ctx_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void userfaultfd_ctx_get(struct userfaultfd_ctx * ctx)
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
