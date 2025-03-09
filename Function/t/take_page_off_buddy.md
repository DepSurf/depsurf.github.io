# Function: <code>take_page_off_buddy</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729136,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:8931",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729136,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751520,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:9156",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751520,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:9421",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207677,
      "name": "take_page_off_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582031856,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
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
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:9474",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985310,
      "name": "take_page_off_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582460048,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:9639",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037806,
      "name": "take_page_off_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582973952,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:6546",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560039,
      "name": "take_page_off_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583185792,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1186
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
bool take_page_off_buddy(struct page * page)
```

```json
{
  "name": "take_page_off_buddy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "take_page_off_buddy",
      "external": true,
      "loc": "mm/page_alloc.c:6685",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464454,
      "name": "take_page_off_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583369920,
      "name": "take_page_off_buddy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool take_page_off_buddy(struct page * page)
```
</details>
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
