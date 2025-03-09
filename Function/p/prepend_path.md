# Function: <code>prepend_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093760,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/dcache.c:2889",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_path",
        "fs/dcache.c:__d_path",
        "fs/dcache.c:d_absolute_path",
        "fs/dcache.c:SyS_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093760,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251216,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/dcache.c:3056",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:SyS_getcwd",
        "fs/dcache.c:d_path",
        "fs/dcache.c:d_absolute_path",
        "fs/dcache.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251216,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329008,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/dcache.c:3066",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:SyS_getcwd",
        "fs/dcache.c:d_path",
        "fs/dcache.c:d_absolute_path",
        "fs/dcache.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329008,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384416,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/dcache.c:3096",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:SyS_getcwd",
        "fs/dcache.c:d_path",
        "fs/dcache.c:d_absolute_path",
        "fs/dcache.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384416,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530064,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/dcache.c:3108",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:SyS_getcwd",
        "fs/dcache.c:d_path",
        "fs/dcache.c:d_absolute_path",
        "fs/dcache.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530064,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581808800,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808800,
      "name": "prepend_path.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895408,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895408,
      "name": "prepend_path.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020432,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020432,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582098352,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098352,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335728,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335728,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387168,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387168,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414544,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414544,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
int prepend_path(const struct path * path, const struct path * root, struct prepend_buffer * p)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736976,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:157",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736976,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
int prepend_path(const struct path * path, const struct path * root, struct prepend_buffer * p)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283232,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:155",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283232,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int prepend_path(const struct path * path, const struct path * root, struct prepend_buffer * p)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866416,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:155",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866416,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int prepend_path(const struct path * path, const struct path * root, struct prepend_buffer * p)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584088176,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:156",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088176,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int prepend_path(const struct path * path, const struct path * root, struct prepend_buffer * p)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304272,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:156",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__do_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304272,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493635192,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__arm64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493635192,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227173820,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__se_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227173820,
      "name": "prepend_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287226448,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__se_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287226448,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273272212,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__se_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273272212,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582067088,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067088,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582004640,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004640,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582058368,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058368,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "prepend_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582130048,
      "name": "prepend_path",
      "external": false,
      "loc": "fs/d_path.c:75",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd",
        "fs/d_path.c:d_path",
        "fs/d_path.c:d_absolute_path",
        "fs/d_path.c:__d_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130048,
      "name": "prepend_path.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct prepend_buffer * p</code>
</li>
<li>
<b>Param removed. </b>
<code>char * * buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int * buflen</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int prepend_path(const struct path * path, const struct path * root, char * * buffer, int * buflen)
```
</details>
</li>
</ul>
