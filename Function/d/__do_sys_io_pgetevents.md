# Function: <code>__do_sys_io_pgetevents</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581938467,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:1904",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582024483,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2125",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582162428,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2086",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582239836,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582474284,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2109",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
long int __do_sys_io_pgetevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __aio_sigset * usig)
```

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531456,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2107",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531456,
      "name": "__do_sys_io_pgetevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
long int __do_sys_io_pgetevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __aio_sigset * usig)
```

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559184,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2104",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559184,
      "name": "__do_sys_io_pgetevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582875436,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2222",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583442564,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2246",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584034036,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2247",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584258724,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2239",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584475508,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2282",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493811372,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__arm64_sys_io_pgetevents"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227326572,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_pgetevents"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287428220,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_pgetevents"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273401068,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_pgetevents"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582208572,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582145484,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582199052,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
  "name": "__do_sys_io_pgetevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582277292,
      "name": "__do_sys_io_pgetevents",
      "external": false,
      "loc": "fs/aio.c:2102",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
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
long int __do_sys_io_pgetevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __aio_sigset * usig)
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
long int __do_sys_io_pgetevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event * events, struct __kernel_timespec * timeout, const struct __aio_sigset * usig)
```
</details>
</li>
</ul>
