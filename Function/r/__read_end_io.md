# Function: <code>__read_end_io</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582826960,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582826960,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138480,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138480,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219216,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219216,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247056,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247056,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589024,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589024,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127808,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:69",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127808,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584761792,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:69",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:bio_post_read_processing",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761792,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:69",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:bio_post_read_processing",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985104,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 693
    },
    {
      "addr": 18446744071596604983,
      "name": "__read_end_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:69",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:bio_post_read_processing",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585216880,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071597510689,
      "name": "__read_end_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494499312,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494499312,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227935184,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227935184,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288264016,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288264016,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273897428,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273897428,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582795696,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795696,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732848,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732848,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784576,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784576,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __read_end_io(struct bio * bio)
```

```json
{
  "name": "__read_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870976,
      "name": "__read_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870976,
      "name": "__read_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void __read_end_io(struct bio * bio)
```
</details>
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
