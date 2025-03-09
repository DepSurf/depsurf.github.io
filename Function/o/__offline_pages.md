# Function: <code>__offline_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587340704,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1714",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587340704,
      "name": "__offline_pages.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1917
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587839008,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1863",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839008,
      "name": "__offline_pages.constprop.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588053792,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1848",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053792,
      "name": "__offline_pages.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588280576,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1615",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280576,
      "name": "__offline_pages.constprop.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588845888,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1605",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845888,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2015
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589225008,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1614",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589225008,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2055
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589467664,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1571",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589467664,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2206
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589928880,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1525",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928880,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590156096,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1500",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590156096,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173744,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1474",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173744,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1017
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286556144,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1500",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286556144,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1988
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758384,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1500",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758384,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589482608,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1500",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482608,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201792,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1500",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201792,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "__offline_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590252192,
      "name": "__offline_pages",
      "external": false,
      "loc": "mm/memory_hotplug.c:1500",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590252192,
      "name": "__offline_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1389
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn)
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
