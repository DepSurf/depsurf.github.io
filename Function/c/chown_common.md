# Function: <code>chown_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int chown_common(struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982336,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:571",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982336,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137520,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:571",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137520,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212688,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:588",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212688,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258896,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:584",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258896,
      "name": "chown_common",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398032,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:584",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398032,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552224,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:615",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552224,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637456,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:604",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637456,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754096,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754096,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826304,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826304,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582047632,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:653",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047632,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102768,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:643",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102768,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127616,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:645",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127616,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582444256,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:642",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444256,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582962448,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:666",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962448,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583521152,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:702",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583521152,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736608,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:733",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736608,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938496,
      "name": "chown_common",
      "external": true,
      "loc": "fs/open.c:753",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat",
        "fs/init.c:init_chown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938496,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493289672,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493289672,
      "name": "chown_common",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226894204,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226894204,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286826576,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286826576,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273036760,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273036760,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795040,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795040,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732704,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732704,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786352,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786352,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int chown_common(const struct path * path, uid_t user, gid_t group)
```

```json
{
  "name": "chown_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855488,
      "name": "chown_common",
      "external": false,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:do_fchownat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855488,
      "name": "chown_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
