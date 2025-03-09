# Function: <code>watch_queue_set_size</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257520,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:216",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257520,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581299600,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:216",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299600,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317136,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:216",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317136,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:217",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592189094,
      "name": "watch_queue_set_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581562496,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:242",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964259,
      "name": "watch_queue_set_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581915424,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:242",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023892,
      "name": "watch_queue_set_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582350608,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:238",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596546087,
      "name": "watch_queue_set_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582553504,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```

```json
{
  "name": "watch_queue_set_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "watch_queue_set_size",
      "external": true,
      "loc": "kernel/watch_queue.c:238",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449866,
      "name": "watch_queue_set_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582724080,
      "name": "watch_queue_set_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
long int watch_queue_set_size(struct pipe_inode_info * pipe, unsigned int nr_notes)
```
</details>
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
