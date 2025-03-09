# Function: <code>bpf_mkobj_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct inode * dir, struct dentry * dentry, umode_t mode, const struct inode_operations * iops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580380416,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:150",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380416,
      "name": "bpf_mkobj_ops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int bpf_mkobj_ops(struct inode * dir, struct dentry * dentry, umode_t mode, const struct inode_operations * iops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440512,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:142",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440512,
      "name": "bpf_mkobj_ops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580495357,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:152",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580523659,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:153",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580586011,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:153",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkobj",
        "kernel/bpf/inode.c:bpf_mkobj"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580680256,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:309",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580751002,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:309",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580833738,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580884778,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581025371,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:329",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031008,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:330",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_iter_link_pin_kernel",
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031008,
      "name": "bpf_mkobj_ops",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042256,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:331",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042256,
      "name": "bpf_mkobj_ops",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265024,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:331",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265024,
      "name": "bpf_mkobj_ops",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556096,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:331",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556096,
      "name": "bpf_mkobj_ops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928400,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:331",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928400,
      "name": "bpf_mkobj_ops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111808,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:331",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111808,
      "name": "bpf_mkobj_ops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252032,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:328",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252032,
      "name": "bpf_mkobj_ops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492210832,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226108356,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285431268,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272359670,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853578,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580799754,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580844826,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
  "name": "bpf_mkobj_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580903114,
      "name": "bpf_mkobj_ops",
      "external": false,
      "loc": "kernel/bpf/inode.c:306",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog"
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int bpf_mkobj_ops(struct inode * dir, struct dentry * dentry, umode_t mode, const struct inode_operations * iops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int bpf_mkobj_ops(struct dentry * dentry, umode_t mode, void * raw, const struct inode_operations * iops, const struct file_operations * fops)
```
</details>
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
