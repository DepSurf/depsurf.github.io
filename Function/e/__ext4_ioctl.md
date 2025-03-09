# Function: <code>__ext4_ioctl</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122720,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:812",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122720,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3972
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583147920,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:803",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147920,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3503
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:852",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488368,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3815
    },
    {
      "addr": 18446744071592260010,
      "name": "__ext4_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:1134",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014880,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4082
    },
    {
      "addr": 18446744071594041460,
      "name": "__ext4_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645392,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:1216",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645392,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4920
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869136,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:1223",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869136,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4448
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "__ext4_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585102016,
      "name": "__ext4_ioctl",
      "external": false,
      "loc": "fs/ext4/ioctl.c:1233",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585102016,
      "name": "__ext4_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4422
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
long int __ext4_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
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
