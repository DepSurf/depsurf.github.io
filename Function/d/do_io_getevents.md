# Function: <code>do_io_getevents</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769504,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:1835",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:SyS_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769504,
      "name": "do_io_getevents",
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938016,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:1850",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__x32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938016,
      "name": "do_io_getevents",
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024032,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2067",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__x32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024032,
      "name": "do_io_getevents",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161952,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2028",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161952,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239360,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239360,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473808,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2051",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473808,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531024,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2049",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531024,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558752,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2046",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558752,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874928,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2164",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x64_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874928,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442000,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2188",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442000,
      "name": "do_io_getevents",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033440,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2189",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033440,
      "name": "do_io_getevents",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258128,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2181",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258128,
      "name": "do_io_getevents",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584474912,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2224",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474912,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493810800,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_getevents_time32",
        "fs/aio.c:__arm64_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493810800,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227318816,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_getevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227318816,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287427488,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__se_compat_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287427488,
      "name": "do_io_getevents",
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273391868,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273391868,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208096,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208096,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145008,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145008,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582198576,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198576,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec64 * ts)
```

```json
{
  "name": "do_io_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276800,
      "name": "do_io_getevents",
      "external": false,
      "loc": "fs/aio.c:2044",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276800,
      "name": "do_io_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct timespec * ts)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * ts</code> ➡️ <code>struct timespec64 * ts</code>
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
