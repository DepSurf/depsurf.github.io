# Function: <code>strset_include</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589888048,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:117",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/strset.c:strset_prepare_data"
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
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589927392,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:119",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/strset.c:strset_prepare_data"
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
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589835798,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:144",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/strset.c:strset_prepare_data"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool strset_include(const struct strset_req_info * info, const struct strset_reply_data * data, u32 id)
```

```json
{
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590597075,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:144",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590596992,
      "name": "strset_include",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592712323,
      "name": "strset_include.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool strset_include(const struct strset_req_info * info, const struct strset_reply_data * data, u32 id)
```

```json
{
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592217109,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:144",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592217024,
      "name": "strset_include",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071594598384,
      "name": "strset_include.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool strset_include(const struct strset_req_info * info, const struct strset_reply_data * data, u32 id)
```

```json
{
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594047173,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:144",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594047088,
      "name": "strset_include",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071596334299,
      "name": "strset_include.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool strset_include(const struct strset_req_info * info, const struct strset_reply_data * data, u32 id)
```

```json
{
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594425638,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:144",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594425536,
      "name": "strset_include",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071596863273,
      "name": "strset_include.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool strset_include(const struct strset_req_info * info, const struct strset_reply_data * data, u32 id)
```

```json
{
  "name": "strset_include",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595227878,
      "name": "strset_include",
      "external": false,
      "loc": "net/ethtool/strset.c:144",
      "file": "net/ethtool/strset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_reply_size",
        "net/ethtool/strset.c:strset_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595227776,
      "name": "strset_include",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071597788346,
      "name": "strset_include.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool strset_include(const struct strset_req_info * info, const struct strset_reply_data * data, u32 id)
```
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
