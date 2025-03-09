# Function: <code>vt_resizex</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:766",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578688,
      "name": "vt_resizex.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071591458992,
      "name": "vt_resizex.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586462608,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:668",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586462608,
      "name": "vt_resizex",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586990256,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:668",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990256,
      "name": "vt_resizex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288064,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:668",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288064,
      "name": "vt_resizex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589705088,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:668",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589705088,
      "name": "vt_resizex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590009776,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:668",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590009776,
      "name": "vt_resizex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```

```json
{
  "name": "vt_resizex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590348352,
      "name": "vt_resizex",
      "external": false,
      "loc": "drivers/tty/vt/vt_ioctl.c:668",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348352,
      "name": "vt_resizex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int vt_resizex(struct vc_data * vc, struct vt_consize * cs)
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
