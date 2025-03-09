# Function: <code>path_mount</code>

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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301232,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3145",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301232,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3178",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282737,
      "name": "path_mount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582328000,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2069
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3252",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592230906,
      "name": "path_mount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071582648496,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2172
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3295",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594010873,
      "name": "path_mount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583187504,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2158
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3400",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596051662,
      "name": "path_mount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583762816,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2080
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3587",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596574192,
      "name": "path_mount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583979968,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2080
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
```

```json
{
  "name": "path_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "path_mount",
      "external": true,
      "loc": "fs/namespace.c:3604",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/init.c:init_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597478730,
      "name": "path_mount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584192496,
      "name": "path_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2083
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
int path_mount(const char * dev_name, struct path * path, const char * type_page, long unsigned int flags, void * data_page)
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
