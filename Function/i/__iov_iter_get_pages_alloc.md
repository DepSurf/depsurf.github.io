# Function: <code>__iov_iter_get_pages_alloc</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, size_t * start, unsigned int gup_flags)
```

```json
{
  "name": "__iov_iter_get_pages_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iov_iter_get_pages_alloc",
      "external": false,
      "loc": "lib/iov_iter.c:1432",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc2",
        "lib/iov_iter.c:iov_iter_get_pages2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047760,
      "name": "__iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
    },
    {
      "addr": 18446744071596114081,
      "name": "__iov_iter_get_pages_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
ssize_t __iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "__iov_iter_get_pages_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iov_iter_get_pages_alloc",
      "external": false,
      "loc": "lib/iov_iter.c:1083",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312576,
      "name": "__iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1019
    },
    {
      "addr": 18446744071596639961,
      "name": "__iov_iter_get_pages_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
ssize_t __iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "__iov_iter_get_pages_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iov_iter_get_pages_alloc",
      "external": false,
      "loc": "lib/iov_iter.c:980",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598192,
      "name": "__iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1063
    },
    {
      "addr": 18446744071597548357,
      "name": "__iov_iter_get_pages_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
ssize_t __iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, size_t * start, unsigned int gup_flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int gup_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
