# Function: <code>try_remove_memory</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589926176,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1767",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589926176,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590152272,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1754",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590152272,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591170640,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1760",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591170640,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591666656,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1722",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591666656,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591610640,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1978",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591610640,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int try_remove_memory(u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592783952,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:2146",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592783952,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594682640,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:2068",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594682640,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596418992,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:2064",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596418992,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596959056,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:2037",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596959056,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597886752,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:2249",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597886752,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286550864,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1754",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286550864,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589754560,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1754",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589754560,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589478784,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1754",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589478784,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590197968,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1754",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197968,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int try_remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "try_remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248384,
      "name": "try_remove_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1754",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:__remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248384,
      "name": "try_remove_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size</code> ➡️ <code>start, size</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size)
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
int try_remove_memory(int nid, u64 start, u64 size)
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
