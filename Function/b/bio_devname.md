# Function: <code>bio_devname</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667920,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667920,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583775024,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775024,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964864,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964864,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068224,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068224,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339040,
      "name": "bio_devname",
      "external": true,
      "loc": "block/bio.c:731",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector",
        "block/blk-core.c:blkcg_bio_issue_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339040,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456784,
      "name": "bio_devname",
      "external": true,
      "loc": "block/bio.c:731",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456784,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584491888,
      "name": "bio_devname",
      "external": true,
      "loc": "block/bio.c:687",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:submit_bio_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491888,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584900752,
      "name": "bio_devname",
      "external": true,
      "loc": "block/bio.c:770",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:submit_bio_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900752,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495911512,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495911512,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229254004,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229254004,
      "name": "bio_devname",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290120752,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290120752,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275025564,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275025564,
      "name": "bio_devname",
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036960,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036960,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972720,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972720,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020720,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020720,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
const char * bio_devname(struct bio * bio, char * buf)
```

```json
{
  "name": "bio_devname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123264,
      "name": "bio_devname",
      "external": true,
      "loc": "block/partition-generic.c:54",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:handle_bad_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123264,
      "name": "bio_devname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
const char * bio_devname(struct bio * bio, char * buf)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
const char * bio_devname(struct bio * bio, char * buf)
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
