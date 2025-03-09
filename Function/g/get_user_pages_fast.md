# Function: <code>get_user_pages_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311024,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "arch/x86/mm/gup.c:323",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/trace/trace.c:tracing_mark_write",
        "mm/madvise.c:SyS_madvise",
        "fs/splice.c:vmsplice_to_pipe",
        "block/bio.c:bio_map_user_iov",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311024,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311744,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "arch/x86/mm/gup.c:370",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/trace/trace.c:tracing_mark_write",
        "mm/madvise.c:SyS_madvise",
        "fs/splice.c:vmsplice_to_pipe",
        "block/bio.c:bio_map_user_iov",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311744,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326960,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "arch/x86/mm/gup.c:374",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:SyS_madvise",
        "block/bio.c:bio_map_user_iov",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326960,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800896,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/util.c:312",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:SyS_madvise",
        "block/bio.c:bio_map_user_iov",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881472,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889600,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/util.c:312",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:SyS_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974704,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025344,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/util.c:336",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:madvise_inject_error",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109216,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102864,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/util.c:329",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:madvise_inject_error",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189248,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260544,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2403",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__do_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260544,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319216,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__do_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319216,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513056,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2884",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:madvise_inject_error",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513056,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553600,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2677",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553600,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576496,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2743",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576496,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841152,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2838",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841152,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233600,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2988",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "mm/madvise.c:madvise_inject_error",
        "mm/mempolicy.c:do_get_mempolicy",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233600,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723936,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:3014",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "mm/madvise.c:madvise_inject_error",
        "mm/mempolicy.c:do_get_mempolicy",
        "lib/iov_iter.c:__iov_iter_get_pages_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723936,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940288,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:3264",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "mm/madvise.c:do_madvise",
        "mm/mempolicy.c:do_get_mempolicy",
        "lib/iov_iter.c:__iov_iter_get_pages_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940288,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115504,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:3282",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "mm/madvise.c:do_madvise",
        "mm/mempolicy.c:do_get_mempolicy",
        "lib/iov_iter.c:__iov_iter_get_pages_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115504,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492725288,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__arm64_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492725288,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226556280,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226556280,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286071152,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__se_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286071152,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272717482,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272717482,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288064,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__do_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288064,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233872,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__do_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233872,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279264,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__do_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279264,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages_fast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343184,
      "name": "get_user_pages_fast",
      "external": true,
      "loc": "mm/gup.c:2419",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "mm/madvise.c:__do_sys_madvise",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343184,
      "name": "get_user_pages_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
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
