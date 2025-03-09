# Function: <code>__nr_hugepages_store_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580795022,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2261",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:nr_hugepages_store_common",
        "mm/hugetlb.c:hugetlb_sysctl_handler_common"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580918955,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2312",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985248,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2418",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985248,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031200,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2396",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031200,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140816,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2404",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140816,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1626
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282096,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2406",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282096,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366688,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2400",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366688,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475088,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2477",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475088,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539216,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539216,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750016,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2877",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750016,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798160,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2830",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798160,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826288,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2995",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826288,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115584,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:3280",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115584,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558288,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:3552",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558288,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583081136,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:3720",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081136,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291664,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:3750",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291664,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583520976,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:4008",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_mempolicy_store",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520976,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492973916,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286391312,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286391312,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272887460,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_sysctl_handler",
        "mm/hugetlb.c:nr_hugepages_store"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581507952,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507952,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450144,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450144,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499264,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499264,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```

```json
{
  "name": "__nr_hugepages_store_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581565888,
      "name": "__nr_hugepages_store_common",
      "external": false,
      "loc": "mm/hugetlb.c:2594",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565888,
      "name": "__nr_hugepages_store_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate * h, int nid, long unsigned int count, size_t len)
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
