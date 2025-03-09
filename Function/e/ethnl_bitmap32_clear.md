# Function: <code>ethnl_bitmap32_clear</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589882064,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882064,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589921248,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921248,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589828864,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828864,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593136,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071592712072,
      "name": "ethnl_bitmap32_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592212912,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071594598145,
      "name": "ethnl_bitmap32_clear.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594042752,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071596334084,
      "name": "ethnl_bitmap32_clear.cold",
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
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594421056,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071596863058,
      "name": "ethnl_bitmap32_clear.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
```

```json
{
  "name": "ethnl_bitmap32_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitmap32_clear",
      "external": false,
      "loc": "net/ethtool/bitset.c:34",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595223296,
      "name": "ethnl_bitmap32_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071597788131,
      "name": "ethnl_bitmap32_clear.cold",
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
void ethnl_bitmap32_clear(u32 * dst, unsigned int start, unsigned int end, bool * mod)
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
