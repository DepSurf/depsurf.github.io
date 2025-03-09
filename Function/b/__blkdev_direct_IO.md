# Function: <code>__blkdev_direct_IO</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581481084,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:326",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581536064,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:332",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581678721,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:320",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581844654,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:323",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581932551,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:340",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066032,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066032,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582143680,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143680,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382656,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:337",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382656,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438080,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:369",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438080,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, unsigned int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464816,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:369",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464816,
      "name": "__blkdev_direct_IO",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, unsigned int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "block/fops.c:191",
      "file": "block/fops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898400,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1091
    },
    {
      "addr": 18446744071592312554,
      "name": "__blkdev_direct_IO.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, unsigned int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "block/fops.c:164",
      "file": "block/fops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597728,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071594095401,
      "name": "__blkdev_direct_IO.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, unsigned int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "block/fops.c:170",
      "file": "block/fops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586365408,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
    },
    {
      "addr": 18446744071596104590,
      "name": "__blkdev_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "block/fops.c:170",
      "file": "block/fops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611392,
      "name": "__blkdev_direct_IO.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 954
    },
    {
      "addr": 18446744071596628434,
      "name": "__blkdev_direct_IO.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "block/fops.c:162",
      "file": "block/fops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586880768,
      "name": "__blkdev_direct_IO.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
    },
    {
      "addr": 18446744071597534288,
      "name": "__blkdev_direct_IO.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493698320,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227221744,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227221744,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287303484,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273315528,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO"
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112416,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112416,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049856,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049856,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102896,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102896,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```

```json
{
  "name": "__blkdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176080,
      "name": "__blkdev_direct_IO",
      "external": false,
      "loc": "fs/block_dev.c:338",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176080,
      "name": "__blkdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_pages</code> ➡️ <code>unsigned int nr_pages</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, unsigned int nr_pages)
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
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb * iocb, struct iov_iter * iter, int nr_pages)
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
