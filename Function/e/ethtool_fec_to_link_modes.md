# Function: <code>ethtool_fec_to_link_modes</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```

```json
{
  "name": "ethtool_fec_to_link_modes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589861253,
      "name": "ethtool_fec_to_link_modes",
      "external": false,
      "loc": "net/ethtool/fec.c:32",
      "file": "net/ethtool/fec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860176,
      "name": "ethtool_fec_to_link_modes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```

```json
{
  "name": "ethtool_fec_to_link_modes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590622412,
      "name": "ethtool_fec_to_link_modes",
      "external": false,
      "loc": "net/ethtool/fec.c:32",
      "file": "net/ethtool/fec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621344,
      "name": "ethtool_fec_to_link_modes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```

```json
{
  "name": "ethtool_fec_to_link_modes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592244415,
      "name": "ethtool_fec_to_link_modes",
      "external": false,
      "loc": "net/ethtool/fec.c:32",
      "file": "net/ethtool/fec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592243264,
      "name": "ethtool_fec_to_link_modes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```

```json
{
  "name": "ethtool_fec_to_link_modes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594075920,
      "name": "ethtool_fec_to_link_modes",
      "external": false,
      "loc": "net/ethtool/fec.c:32",
      "file": "net/ethtool/fec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/fec.c:fec_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594075920,
      "name": "ethtool_fec_to_link_modes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```

```json
{
  "name": "ethtool_fec_to_link_modes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594455280,
      "name": "ethtool_fec_to_link_modes",
      "external": false,
      "loc": "net/ethtool/fec.c:32",
      "file": "net/ethtool/fec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/fec.c:fec_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594455280,
      "name": "ethtool_fec_to_link_modes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```

```json
{
  "name": "ethtool_fec_to_link_modes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595257552,
      "name": "ethtool_fec_to_link_modes",
      "external": false,
      "loc": "net/ethtool/fec.c:32",
      "file": "net/ethtool/fec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/fec.c:fec_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595257552,
      "name": "ethtool_fec_to_link_modes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int * link_modes, u8 * fec_auto)
```
</details>
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
