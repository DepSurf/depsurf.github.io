# Function: <code>__delayacct_thrashing_end</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580401232,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:180",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401232,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580454000,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454000,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502960,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502960,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589120,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589120,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580578400,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578400,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581280,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581280,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752080,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:206",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752080,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966688,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:222",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:migration_entry_wait_on_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966688,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __delayacct_thrashing_end(bool * in_thrashing)
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:227",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/page_io.c:swap_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596001844,
      "name": "__delayacct_thrashing_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581262176,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __delayacct_thrashing_end(bool * in_thrashing)
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:230",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/page_io.c:swap_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596520405,
      "name": "__delayacct_thrashing_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581357280,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __delayacct_thrashing_end(bool * in_thrashing)
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:230",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/page_io.c:swap_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597420790,
      "name": "__delayacct_thrashing_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581463392,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491781456,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491781456,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225728928,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225728928,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284828688,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284828688,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272097184,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272097184,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471760,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471760,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580418800,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418800,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463008,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463008,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __delayacct_thrashing_end()
```

```json
{
  "name": "__delayacct_thrashing_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518672,
      "name": "__delayacct_thrashing_end",
      "external": true,
      "loc": "kernel/delayacct.c:171",
      "file": "kernel/delayacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518672,
      "name": "__delayacct_thrashing_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __delayacct_thrashing_end()
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * in_thrashing</code>
</li>
</ul>
</details>
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
