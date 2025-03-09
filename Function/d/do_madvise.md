# Function: <code>do_madvise</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581689577,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1054",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688400,
      "name": "do_madvise.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1069
    },
    {
      "addr": 18446744071581694560,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735598,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1058",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733296,
      "name": "do_madvise.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1702
    },
    {
      "addr": 18446744071591331418,
      "name": "do_madvise.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071581741456,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581764003,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1059",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761472,
      "name": "do_madvise.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1944
    },
    {
      "addr": 18446744071591273798,
      "name": "do_madvise.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071581769712,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582046502,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1128",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043536,
      "name": "do_madvise.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2456
    },
    {
      "addr": 18446744071592208240,
      "name": "do_madvise.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582052368,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484912,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1368",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "io_uring/io_uring.c:io_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484912,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999264,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1402",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "io_uring/advise.c:io_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999264,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1404",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "io_uring/advise.c:io_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560585,
      "name": "do_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583207632,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int do_madvise(struct mm_struct * mm, long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "do_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_madvise",
      "external": true,
      "loc": "mm/madvise.c:1398",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "io_uring/advise.c:io_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597466278,
      "name": "do_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583443200,
      "name": "do_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int do_madvise(long unsigned int start, size_t len_in, int behavior)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, len_in, behavior</code> ➡️ <code>mm, start, len_in, behavior</code>
</li>
</ul>
</details>
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
