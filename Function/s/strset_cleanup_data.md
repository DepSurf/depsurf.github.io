# Function: <code>strset_cleanup_data</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589889302,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:196",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886800,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589928582,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:197",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589926112,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589835524,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:222",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589833984,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:222",
      "file": "net/ethtool/strset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590596896,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071592712302,
      "name": "strset_cleanup_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:222",
      "file": "net/ethtool/strset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592216912,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071594598363,
      "name": "strset_cleanup_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:222",
      "file": "net/ethtool/strset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594046960,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071596334278,
      "name": "strset_cleanup_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:222",
      "file": "net/ethtool/strset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594425312,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071596863252,
      "name": "strset_cleanup_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```

```json
{
  "name": "strset_cleanup_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strset_cleanup_data",
      "external": false,
      "loc": "net/ethtool/strset.c:222",
      "file": "net/ethtool/strset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595227552,
      "name": "strset_cleanup_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071597788325,
      "name": "strset_cleanup_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data * reply_base)
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
