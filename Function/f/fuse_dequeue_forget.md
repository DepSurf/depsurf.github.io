# Function: <code>fuse_dequeue_forget</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583171568,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167072,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583494485,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1050",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_read_single_forget"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489584,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583602869,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1071",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_read_single_forget"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598048,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583625525,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1068",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621072,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984549,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1084",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980096,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562032,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1076",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562032,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585239520,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1077",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239520,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585475118,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1079",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469088,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585710142,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1079",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704112,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494879800,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494879800,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228305016,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228295516,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288754376,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288740192,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274201840,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274197272,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583140304,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135808,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583077456,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072960,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583124336,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119840,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```

```json
{
  "name": "fuse_dequeue_forget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583216605,
      "name": "fuse_dequeue_forget",
      "external": true,
      "loc": "fs/fuse/dev.c:1051",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213584,
      "name": "fuse_dequeue_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct fuse_forget_link * fuse_dequeue_forget(struct fuse_iqueue * fiq, unsigned int max, unsigned int * countp)
```
</details>
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
