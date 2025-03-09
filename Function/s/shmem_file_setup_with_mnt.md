# Function: <code>shmem_file_setup_with_mnt</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580867104,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4303",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867104,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581009648,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4019",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009648,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096432,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:3978",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096432,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581150128,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4059",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150128,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581208016,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208016,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408752,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4144",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408752,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437232,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4251",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437232,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457632,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4195",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457632,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711344,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4131",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711344,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083360,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4143",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083360,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560976,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4272",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560976,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763488,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4481",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763488,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582944464,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4856",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944464,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492591400,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492591400,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226444808,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226444808,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285900112,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285900112,
      "name": "shmem_file_setup_with_mnt",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272627146,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272627146,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581176864,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176864,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581123680,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123680,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581168064,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168064,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```

```json
{
  "name": "shmem_file_setup_with_mnt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581224816,
      "name": "shmem_file_setup_with_mnt",
      "external": true,
      "loc": "mm/shmem.c:4181",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224816,
      "name": "shmem_file_setup_with_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct file * shmem_file_setup_with_mnt(struct vfsmount * mnt, const char * name, loff_t size, long unsigned int flags)
```
</details>
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
