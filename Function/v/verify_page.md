# Function: <code>verify_page</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323040,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
    },
    {
      "addr": 18446744071582325141,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582612384,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1517
    },
    {
      "addr": 18446744071582614501,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684192,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
    },
    {
      "addr": 18446744071591344020,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714208,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1515
    },
    {
      "addr": 18446744071591286808,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040832,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1763
    },
    {
      "addr": 18446744071592243560,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583515776,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2079
    },
    {
      "addr": 18446744071594022624,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:76",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114352,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2471
    },
    {
      "addr": 18446744071596059241,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493904320,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493904320,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1544
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227382936,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227382936,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1672
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287541664,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287541664,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2176
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273460584,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273460584,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1276
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291776,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
    },
    {
      "addr": 18446744071582293877,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229536,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
    },
    {
      "addr": 18446744071582231637,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282256,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
    },
    {
      "addr": 18446744071582284357,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```

```json
{
  "name": "verify_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_page",
      "external": false,
      "loc": "fs/verity/verify.c:86",
      "file": "fs/verity/verify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360848,
      "name": "verify_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
    },
    {
      "addr": 18446744071582362949,
      "name": "verify_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int level0_ra_pages</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool verify_page(struct inode * inode, const struct fsverity_info * vi, struct ahash_request * req, struct page * data_page, long unsigned int level0_ra_pages)
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
