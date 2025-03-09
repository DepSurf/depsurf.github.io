# Function: <code>chmod_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int chmod_common(struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981952,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:506",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981952,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137136,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:506",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137136,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212304,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:523",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212304,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257840,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:519",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257840,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396960,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:519",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396960,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551776,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:539",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551776,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637072,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:528",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637072,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753712,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753712,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825920,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825920,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046592,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:577",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046592,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101728,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:567",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101728,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126576,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:568",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126576,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443216,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:565",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443216,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582961232,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:589",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961232,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519792,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:589",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519792,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583735232,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:626",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735232,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583936256,
      "name": "chmod_common",
      "external": true,
      "loc": "fs/open.c:631",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/init.c:init_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936256,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493289336,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493289336,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226893860,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226893860,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286826096,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286826096,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273036478,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273036478,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794656,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794656,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732320,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732320,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785968,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785968,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int chmod_common(const struct path * path, umode_t mode)
```

```json
{
  "name": "chmod_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855104,
      "name": "chmod_common",
      "external": false,
      "loc": "fs/open.c:548",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_fchmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855104,
      "name": "chmod_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
