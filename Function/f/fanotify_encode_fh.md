# Function: <code>fanotify_encode_fh</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:280",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425488,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071582428818,
      "name": "fanotify_encode_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:331",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479632,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071591341040,
      "name": "fanotify_encode_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:361",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582506576,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071591283741,
      "name": "fanotify_encode_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:361",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821776,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071592236471,
      "name": "fanotify_encode_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:399",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378400,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071594016657,
      "name": "fanotify_encode_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963328,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:402",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963328,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186752,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:403",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186752,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, unsigned int fh_len, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_encode_fh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584400736,
      "name": "fanotify_encode_fh",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:397",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400736,
      "name": "fanotify_encode_fh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void fanotify_encode_fh(struct fanotify_fh * fh, struct inode * inode, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int fh_len</code>
</li>
<li>
<b>Param reordered. </b>
<code>fh, inode, gfp</code> ➡️ <code>fh, inode, fh_len, gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int * hash</code>
</li>
<li>
<b>Param reordered. </b>
<code>fh, inode, fh_len, gfp</code> ➡️ <code>fh, inode, fh_len, hash, gfp</code>
</li>
</ul>
</details>
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
