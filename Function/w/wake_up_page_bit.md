# Function: <code>wake_up_page_bit</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580611296,
      "name": "wake_up_page_bit",
      "external": true,
      "loc": "mm/filemap.c:791",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611296,
      "name": "wake_up_page_bit",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639776,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:912",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639776,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722416,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1013",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722416,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857760,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1013",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857760,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926176,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:998",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926176,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581022224,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1046",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022224,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077472,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077472,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264896,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1030",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264896,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306816,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1100",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306816,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324256,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1124",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_private_2",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324256,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569840,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1179",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_private_2",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569840,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492445720,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492445720,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226317020,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226317020,
      "name": "wake_up_page_bit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285713584,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285713584,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272517254,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272517254,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046320,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046320,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993600,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993600,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037520,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037520,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void wake_up_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wake_up_page_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099136,
      "name": "wake_up_page_bit",
      "external": false,
      "loc": "mm/filemap.c:1055",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099136,
      "name": "wake_up_page_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void wake_up_page_bit(struct page * page, int bit_nr)
```
</details>
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
void wake_up_page_bit(struct page * page, int bit_nr)
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
