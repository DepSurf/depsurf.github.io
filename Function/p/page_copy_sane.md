# Function: <code>page_copy_sane</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583456263,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:688",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583636712,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:688",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583856730,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:818",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583937690,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:862",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584116104,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132335,
      "name": "page_copy_sane.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584239239,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584650919,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:884",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584766499,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:891",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584798890,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:936",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585222091,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:779",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool page_copy_sane(struct page * page, size_t offset, size_t n)
```

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:831",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586058176,
      "name": "page_copy_sane",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071594127046,
      "name": "page_copy_sane.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
bool page_copy_sane(struct page * page, size_t offset, size_t n)
```

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:689",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042336,
      "name": "page_copy_sane",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071596114017,
      "name": "page_copy_sane.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587315473,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:445",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_to_iter_nofault"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587600908,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:326",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_to_iter_nofault"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496116416,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229441128,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290384364,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275179438,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584207975,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584143191,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584191735,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
  "name": "page_copy_sane",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584296174,
      "name": "page_copy_sane",
      "external": false,
      "loc": "lib/iov_iter.c:863",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool page_copy_sane(struct page * page, size_t offset, size_t n)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool page_copy_sane(struct page * page, size_t offset, size_t n)
```
</details>
</li>
</ul>
