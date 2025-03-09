# Function: <code>ksys_shmctl</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf)
```

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903792,
      "name": "ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1111",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903792,
      "name": "ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf)
```

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012080,
      "name": "ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012080,
      "name": "ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583192896,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192896,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583298704,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298704,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583630304,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630304,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583750912,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1139",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750912,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583775056,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1139",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775056,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584137152,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1235",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137152,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584735424,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1229",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735424,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585429216,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1245",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585429216,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585659920,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1245",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659920,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585906688,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1241",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585906688,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495037160,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__arm64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495037160,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf, int version)
```

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228437848,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:ksys_old_shmctl",
        "ipc/shm.c:__se_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228437848,
      "name": "ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf, int version)
```

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288922848,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:ksys_old_shmctl",
        "ipc/shm.c:__se_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288922848,
      "name": "ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274313866,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__se_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274313866,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1678
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583267440,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267440,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583204576,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583204576,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583251472,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251472,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344080,
      "name": "ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1140",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_sys_shmctl",
        "ipc/shm.c:__x64_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344080,
      "name": "ksys_shmctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf, int version)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long int ksys_shmctl(int shmid, int cmd, struct shmid_ds * buf, int version)
```
</details>
</li>
</ul>
