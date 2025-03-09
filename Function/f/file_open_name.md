# Function: <code>file_open_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988656,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:971",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988656,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143600,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:964",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143600,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218784,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:981",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218784,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265728,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:987",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265728,
      "name": "file_open_name",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404864,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:987",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404864,
      "name": "file_open_name",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559648,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1029",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559648,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644800,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1016",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644800,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761536,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1036",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761536,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833744,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833744,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056944,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1118",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056944,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106800,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1111",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106800,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582131744,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1133",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131744,
      "name": "file_open_name",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448400,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1151",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448400,
      "name": "file_open_name",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966880,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1216",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966880,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526048,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1248",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526048,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741472,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1345",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741472,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943360,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1342",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943360,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493297008,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__arm64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493297008,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226900096,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226900096,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286835952,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286835952,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273041834,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273041834,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802480,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802480,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740144,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740144,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793792,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793792,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct file * file_open_name(struct filename * name, int flags, umode_t mode)
```

```json
{
  "name": "file_open_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862928,
      "name": "file_open_name",
      "external": true,
      "loc": "fs/open.c:1041",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:filp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862928,
      "name": "file_open_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
