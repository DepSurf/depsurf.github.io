# Function: <code>init_chroot</code>

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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612324502,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612324502,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614464687,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614464687,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615410728,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615410728,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617203702,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617203702,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627904864,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627904864,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619667904,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619667904,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int init_chroot(const char * filename)
```

```json
{
  "name": "init_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621974032,
      "name": "init_chroot",
      "external": true,
      "loc": "fs/init.c:59",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "drivers/base/devtmpfs.c:devtmpfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621974032,
      "name": "init_chroot",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int init_chroot(const char * filename)
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
