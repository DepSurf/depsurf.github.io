# Function: <code>__do_compat_sys_io_pgetevents_time64</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582026229,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2256",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164637,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2223",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582241701,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582476149,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2246",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_io_pgetevents_time64(compat_aio_context_t ctx_id, compat_long_t min_nr, compat_long_t nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __compat_aio_sigset * usig)
```

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532544,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2244",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532544,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
long int __do_compat_sys_io_pgetevents_time64(compat_aio_context_t ctx_id, compat_long_t min_nr, compat_long_t nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __compat_aio_sigset * usig)
```

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560272,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2241",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560272,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582877125,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2359",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583443588,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2383",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584035092,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2384",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584259796,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2376",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584476580,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2419",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493812828,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287429368,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582210437,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582147013,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582200917,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_io_pgetevents_time64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582278821,
      "name": "__do_compat_sys_io_pgetevents_time64",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_io_pgetevents_time64(compat_aio_context_t ctx_id, compat_long_t min_nr, compat_long_t nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __compat_aio_sigset * usig)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_io_pgetevents_time64(compat_aio_context_t ctx_id, compat_long_t min_nr, compat_long_t nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __compat_aio_sigset * usig)
```
</details>
</li>
</ul>
