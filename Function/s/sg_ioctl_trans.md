# Function: <code>sg_ioctl_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581359042,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:279",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581539763,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:301",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581625139,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:301",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581675810,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:301",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581822626,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:284",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581999344,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:282",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582086453,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248336,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248336,
      "name": "sg_ioctl_trans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582348837,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493941904,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493941904,
      "name": "sg_ioctl_trans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3084
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
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287580304,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:__se_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287580304,
      "name": "sg_ioctl_trans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2588
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317573,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255333,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308053,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_ioctl_trans",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582387285,
      "name": "sg_ioctl_trans",
      "external": false,
      "loc": "fs/compat_ioctl.c:146",
      "file": "fs/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int sg_ioctl_trans(struct file * file, unsigned int cmd, sg_io_hdr32_t * sgio32)
```
</details>
</li>
</ul>
