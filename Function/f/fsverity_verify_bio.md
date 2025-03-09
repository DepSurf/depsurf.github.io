# Function: <code>fsverity_verify_bio</code>

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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324544,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324544,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614000,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:223",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614000,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685808,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:223",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685808,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715824,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:223",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715824,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:223",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592243923,
      "name": "fsverity_verify_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583042704,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:223",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594022970,
      "name": "fsverity_verify_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583517968,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:212",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596059391,
      "name": "fsverity_verify_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584116976,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:308",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596583466,
      "name": "fsverity_verify_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071584343520,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:308",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487867,
      "name": "fsverity_verify_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584562048,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493906032,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493906032,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227384608,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227384608,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287543840,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287543840,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273461860,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273461860,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582293280,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293280,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231040,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231040,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283760,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283760,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void fsverity_verify_bio(struct bio * bio)
```

```json
{
  "name": "fsverity_verify_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362352,
      "name": "fsverity_verify_bio",
      "external": true,
      "loc": "fs/verity/verify.c:221",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362352,
      "name": "fsverity_verify_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void fsverity_verify_bio(struct bio * bio)
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
