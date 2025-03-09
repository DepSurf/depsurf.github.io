# Function: <code>wait_on_page_bit_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480976,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:756",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480976,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560288,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:796",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560288,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580625481,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:890",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627664,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580653605,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1016",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655888,
      "name": "wait_on_page_bit_killable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580740476,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1137",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726624,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580869766,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1137",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863312,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941293,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1171",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932544,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035682,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1219",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026864,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091250,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082208,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581278782,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1203",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268720,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581317643,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1342",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read_pagenotuptodate",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313696,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581346166,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1366",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:wait_on_page_private_2_killable"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_on_page_writeback_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332256,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581593542,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1421",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:wait_on_page_private_2_killable"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_on_page_writeback_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579936,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492456924,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492447984,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226331272,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226320220,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285733848,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285718528,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272528472,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272522218,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581060098,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051056,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581007330,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998336,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581051298,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042256,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit_killable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581112941,
      "name": "wait_on_page_bit_killable",
      "external": true,
      "loc": "mm/filemap.c:1228",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103856,
      "name": "wait_on_page_bit_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int wait_on_page_bit_killable(struct page * page, int bit_nr)
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
