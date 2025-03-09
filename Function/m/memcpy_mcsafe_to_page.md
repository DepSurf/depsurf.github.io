# Function: <code>memcpy_mcsafe_to_page</code>

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
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848960,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:586",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848960,
      "name": "memcpy_mcsafe_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932832,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:630",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932832,
      "name": "memcpy_mcsafe_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111024,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111024,
      "name": "memcpy_mcsafe_to_page",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233824,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233824,
      "name": "memcpy_mcsafe_to_page",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643728,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:649",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:copy_pipe_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643728,
      "name": "memcpy_mcsafe_to_page",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290358768,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290358768,
      "name": "memcpy_mcsafe_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202560,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202560,
      "name": "memcpy_mcsafe_to_page",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137776,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137776,
      "name": "memcpy_mcsafe_to_page",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186320,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186320,
      "name": "memcpy_mcsafe_to_page",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_mcsafe_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290704,
      "name": "memcpy_mcsafe_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:631",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290704,
      "name": "memcpy_mcsafe_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page * page, size_t offset, const char * from, size_t len)
```
</details>
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
