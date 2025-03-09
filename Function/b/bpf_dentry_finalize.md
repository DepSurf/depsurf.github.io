# Function: <code>bpf_dentry_finalize</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494368,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:124",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494368,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522640,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:125",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522640,
      "name": "bpf_dentry_finalize",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584752,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:125",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584752,
      "name": "bpf_dentry_finalize",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680128,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:125",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680128,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750864,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:125",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750864,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833600,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:122",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833600,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884640,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884640,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581023007,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:144",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581029311,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:145",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581040847,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:145",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581263535,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:145",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581554463,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:145",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581926575,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:145",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582111679,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:145",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582251907,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:143",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492209272,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492209272,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226106916,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226106916,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285429360,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285429360,
      "name": "bpf_dentry_finalize",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272358386,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272358386,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853440,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853440,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799616,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799616,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844688,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844688,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```

```json
{
  "name": "bpf_dentry_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902976,
      "name": "bpf_dentry_finalize",
      "external": false,
      "loc": "kernel/bpf/inode.c:123",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902976,
      "name": "bpf_dentry_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
void bpf_dentry_finalize(struct dentry * dentry, struct inode * inode, struct inode * dir)
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
