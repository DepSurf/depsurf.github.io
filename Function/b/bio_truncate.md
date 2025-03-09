# Function: <code>bio_truncate</code>

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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955312,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955312,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584347273,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:555",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
      ],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344208,
      "name": "bio_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071584347152,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584464024,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:557",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
      ],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459264,
      "name": "bio_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071584463888,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584498420,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:521",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
      ],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584493584,
      "name": "bio_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071584498336,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584909188,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:549",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
      ],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902048,
      "name": "bio_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071592312595,
      "name": "bio_truncate.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071584909104,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585608990,
      "name": "bio_truncate",
      "external": false,
      "loc": "block/bio.c:605",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
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
  "name": "bio_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586377918,
      "name": "bio_truncate",
      "external": false,
      "loc": "block/bio.c:630",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
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
  "name": "bio_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586624270,
      "name": "bio_truncate",
      "external": false,
      "loc": "block/bio.c:629",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
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
  "name": "bio_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586895774,
      "name": "bio_truncate",
      "external": false,
      "loc": "block/bio.c:629",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:guard_bio_eod"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495776992,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495776992,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229129024,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229129024,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289951536,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289951536,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274921656,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274921656,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924048,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924048,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860992,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860992,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583907808,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907808,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
void bio_truncate(struct bio * bio, unsigned int new_size)
```

```json
{
  "name": "bio_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009072,
      "name": "bio_truncate",
      "external": true,
      "loc": "block/bio.c:551",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009072,
      "name": "bio_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void bio_truncate(struct bio * bio, unsigned int new_size)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void bio_truncate(struct bio * bio, unsigned int new_size)
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
