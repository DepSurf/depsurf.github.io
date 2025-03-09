# Function: <code>ioc_qos_write</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584162832,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162832,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561392,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2248",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561392,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679664,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3152",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679664,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707744,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3159",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707744,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3161",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131296,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    },
    {
      "addr": 18446744071592320787,
      "name": "ioc_qos_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3169",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852176,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071594105014,
      "name": "ioc_qos_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3177",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586632832,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1338
    },
    {
      "addr": 18446744071596109391,
      "name": "ioc_qos_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3198",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894576,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1592
    },
    {
      "addr": 18446744071596633259,
      "name": "ioc_qos_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:3205",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587172608,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1598
    },
    {
      "addr": 18446744071597539577,
      "name": "ioc_qos_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496015008,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496015008,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229352712,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229352712,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290248032,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290248032,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1576
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275107734,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275107734,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131568,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131568,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067168,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067168,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115328,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115328,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
```

```json
{
  "name": "ioc_qos_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584218448,
      "name": "ioc_qos_write",
      "external": false,
      "loc": "block/blk-iocost.c:2182",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218448,
      "name": "ioc_qos_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
ssize_t ioc_qos_write(struct kernfs_open_file * of, char * input, size_t nbytes, loff_t off)
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
