# Function: <code>loop_set_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584546016,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:905",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584896512,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:900",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585086716,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:876",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585169447,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:906",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585597896,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:895",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585841308,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:946",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585979241,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:943",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586219584,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:961",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219584,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586367632,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586367632,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499210120,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499210120,
      "name": "loop_set_fd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231735892,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231735892,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292420112,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292420112,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1580
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276501704,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276501704,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586129520,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586129520,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585974128,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974128,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586315600,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586315600,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```

```json
{
  "name": "loop_set_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586427152,
      "name": "loop_set_fd",
      "external": false,
      "loc": "drivers/block/loop.c:971",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586427152,
      "name": "loop_set_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int loop_set_fd(struct loop_device * lo, fmode_t mode, struct block_device * bdev, unsigned int arg)
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
