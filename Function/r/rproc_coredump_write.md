# Function: <code>rproc_coredump_write</code>

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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116128,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
    },
    {
      "addr": 18446744071591619893,
      "name": "rproc_coredump_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005968,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071591563275,
      "name": "rproc_coredump_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720352,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071592683985,
      "name": "rproc_coredump_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591230288,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071594569443,
      "name": "rproc_coredump_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592979488,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592979488,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593428448,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593428448,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "rproc_coredump_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594174496,
      "name": "rproc_coredump_write",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_debugfs.c:71",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594174496,
      "name": "rproc_coredump_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
ssize_t rproc_coredump_write(struct file * filp, const char * user_buf, size_t count, loff_t * ppos)
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
