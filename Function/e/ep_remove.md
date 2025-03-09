# Function: <code>ep_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289200,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:692",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_free",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:SyS_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289200,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455136,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:697",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455136,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535920,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:697",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535920,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588896,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:779",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588896,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732752,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:763",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732752,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906368,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:765",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906368,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986960,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986960,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122496,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122496,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199728,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199728,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438304,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:767",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438304,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494064,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:673",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494064,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521568,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:679",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521568,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837536,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:679",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837536,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397408,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:686",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397408,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983824,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:688",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983824,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    }
  ]
}
```
</details>
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493761056,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493761056,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227285000,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227285000,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287380304,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287380304,
      "name": "ep_remove",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273366154,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273366154,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168464,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168464,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109424,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109424,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582158944,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582158944,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```

```json
{
  "name": "ep_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234512,
      "name": "ep_remove",
      "external": false,
      "loc": "fs/eventpoll.c:774",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234512,
      "name": "ep_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int ep_remove(struct eventpoll * ep, struct epitem * epi)
```
</details>
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
