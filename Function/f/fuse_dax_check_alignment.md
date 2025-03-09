# Function: <code>fuse_dax_check_alignment</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1347",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591360466,
      "name": "fuse_dax_check_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583687168,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1347",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303290,
      "name": "fuse_dax_check_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583711696,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1344",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592289308,
      "name": "fuse_dax_check_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584072304,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1372",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594071374,
      "name": "fuse_dax_check_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584663744,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585345984,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1372",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345984,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585576112,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1372",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576112,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
```

```json
{
  "name": "fuse_dax_check_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814576,
      "name": "fuse_dax_check_alignment",
      "external": true,
      "loc": "fs/fuse/dax.c:1371",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:process_init_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814576,
      "name": "fuse_dax_check_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool fuse_dax_check_alignment(struct fuse_conn * fc, unsigned int map_alignment)
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
