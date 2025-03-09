# Function: <code>rproc_coredump_read</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589112544,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:172",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589115632,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589112544,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071589115632,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589002400,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:176",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589005472,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589002400,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071589005472,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589716752,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:176",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589719824,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716752,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071589719824,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224688,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:176",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591227872,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224688,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071591227872,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592973520,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:176",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592976896,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592973520,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071592976896,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593423904,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:176",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593427728,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593423904,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071593427728,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
```

```json
{
  "name": "rproc_coredump_read",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594169984,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:177",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594173776,
      "name": "rproc_coredump_read",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:42",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594169984,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071594173776,
      "name": "rproc_coredump_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
ssize_t rproc_coredump_read(char * buffer, loff_t offset, size_t count, void * data, size_t header_sz)
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
