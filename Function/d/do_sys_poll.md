# Function: <code>do_sys_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081184,
      "name": "do_sys_poll",
      "external": true,
      "loc": "fs/select.c:870",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_restart_poll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081184,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244192,
      "name": "do_sys_poll",
      "external": true,
      "loc": "fs/select.c:876",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_poll",
        "fs/select.c:do_restart_poll",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244192,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321968,
      "name": "do_sys_poll",
      "external": true,
      "loc": "fs/select.c:884",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_poll",
        "fs/select.c:do_restart_poll",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321968,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1356
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374128,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:928",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374128,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515616,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:925",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515616,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1405
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673296,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:926",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673296,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1301
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759584,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:965",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759584,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1313
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581877232,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877232,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949488,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949488,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582183248,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:970",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183248,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230576,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:970",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230576,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256432,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:970",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256432,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574320,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:973",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x64_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x64_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574320,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103408,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:974",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103408,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671792,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:974",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671792,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583889056,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:974",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889056,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096224,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:974",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096224,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493444928,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_compat_sys_ppoll_time64",
        "fs/select.c:__arm64_compat_sys_ppoll_time32",
        "fs/select.c:__arm64_sys_ppoll",
        "fs/select.c:__arm64_sys_poll",
        "fs/select.c:__arm64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493444928,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1728
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227015216,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll_time32",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227015216,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287000208,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_compat_sys_ppoll_time64",
        "fs/select.c:__se_compat_sys_ppoll_time32",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287000208,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1756
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273133606,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273133606,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918224,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918224,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855808,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855808,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909536,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909536,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
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
int do_sys_poll(struct pollfd * ufds, unsigned int nfds, struct timespec64 * end_time)
```

```json
{
  "name": "do_sys_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979168,
      "name": "do_sys_poll",
      "external": false,
      "loc": "fs/select.c:960",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_restart_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979168,
      "name": "do_sys_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
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
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * end_time</code> ➡️ <code>struct timespec64 * end_time</code>
</li>
</ul>
</details>
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
