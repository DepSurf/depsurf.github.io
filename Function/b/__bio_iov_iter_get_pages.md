# Function: <code>__bio_iov_iter_get_pages</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583535313,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:915",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583665399,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:843",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583853928,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:881",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583955928,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341184,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:993",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341184,
      "name": "__bio_iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584458816,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:993",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458816,
      "name": "__bio_iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584499169,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:994",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:1085",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904448,
      "name": "__bio_iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
    },
    {
      "addr": 18446744071592312717,
      "name": "__bio_iov_iter_get_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585610335,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:1205",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:1247",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586378976,
      "name": "__bio_iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 911
    },
    {
      "addr": 18446744071596104725,
      "name": "__bio_iov_iter_get_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:1227",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586625408,
      "name": "__bio_iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    },
    {
      "addr": 18446744071596628582,
      "name": "__bio_iov_iter_get_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:1237",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896960,
      "name": "__bio_iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
    },
    {
      "addr": 18446744071597534635,
      "name": "__bio_iov_iter_get_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495777652,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229129616,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289952476,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274922274,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583924664,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583861608,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583908424,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_iov_iter_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584009720,
      "name": "__bio_iov_iter_get_pages",
      "external": false,
      "loc": "block/bio.c:920",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __bio_iov_iter_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
