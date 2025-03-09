# Function: <code>path_umount</code>

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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582292848,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1738",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292848,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319968,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1753",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319968,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640416,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1754",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640416,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583177568,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1795",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177568,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752480,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1900",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752480,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969472,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1887",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969472,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int path_umount(struct path * path, int flags)
```

```json
{
  "name": "path_umount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181776,
      "name": "path_umount",
      "external": true,
      "loc": "fs/namespace.c:1889",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/init.c:init_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181776,
      "name": "path_umount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int path_umount(struct path * path, int flags)
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
