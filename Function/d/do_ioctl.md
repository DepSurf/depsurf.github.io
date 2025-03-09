# Function: <code>do_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539584,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:128",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539584,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624960,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:128",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624960,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675616,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:128",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675616,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821792,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:127",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821792,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997488,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:125",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997488,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086304,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086304,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248272,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248272,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348096,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348096,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493932680,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493932680,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287577520,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287577520,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316832,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316832,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254592,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254592,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307312,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307312,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "do_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386544,
      "name": "do_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:82",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386544,
      "name": "do_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
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
