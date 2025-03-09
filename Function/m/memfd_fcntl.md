# Function: <code>memfd_fcntl</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548688,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:237",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548688,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633872,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:218",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633872,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751440,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:219",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751440,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823648,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823648,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040592,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040592,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089424,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089424,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114496,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114496,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430864,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:237",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430864,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947296,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:237",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947296,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583504384,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:237",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504384,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
long int memfd_fcntl(struct file * file, unsigned int cmd, unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583719776,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:246",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583719776,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
long int memfd_fcntl(struct file * file, unsigned int cmd, unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920304,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:246",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920304,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493286520,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493286520,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226889648,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226889648,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286822480,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286822480,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273033320,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_sys_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273033320,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792384,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792384,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730048,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730048,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783696,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783696,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "memfd_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852832,
      "name": "memfd_fcntl",
      "external": true,
      "loc": "mm/memfd.c:221",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852832,
      "name": "memfd_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int memfd_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int arg</code> ➡️ <code>unsigned int arg</code>
</li>
</ul>
</details>
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
