# Function: <code>ethtool_rxnfc_copy_to_user</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_to_user(void * useraddr, const struct ethtool_rxnfc * rxnfc, size_t size, const u32 * rule_buf)
```

```json
{
  "name": "ethtool_rxnfc_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590571184,
      "name": "ethtool_rxnfc_copy_to_user",
      "external": false,
      "loc": "net/ethtool/ioctl.c:899",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_get_rxnfc",
        "net/ethtool/ioctl.c:ethtool_set_rxnfc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590571184,
      "name": "ethtool_rxnfc_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int ethtool_rxnfc_copy_to_user(void * useraddr, const struct ethtool_rxnfc * rxnfc, size_t size, const u32 * rule_buf)
```

```json
{
  "name": "ethtool_rxnfc_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592186640,
      "name": "ethtool_rxnfc_copy_to_user",
      "external": false,
      "loc": "net/ethtool/ioctl.c:921",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_get_rxnfc",
        "net/ethtool/ioctl.c:ethtool_set_rxnfc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186640,
      "name": "ethtool_rxnfc_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int ethtool_rxnfc_copy_to_user(void * useraddr, const struct ethtool_rxnfc * rxnfc, size_t size, const u32 * rule_buf)
```

```json
{
  "name": "ethtool_rxnfc_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594015408,
      "name": "ethtool_rxnfc_copy_to_user",
      "external": false,
      "loc": "net/ethtool/ioctl.c:909",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_get_rxnfc",
        "net/ethtool/ioctl.c:ethtool_set_rxnfc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594015408,
      "name": "ethtool_rxnfc_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int ethtool_rxnfc_copy_to_user(void * useraddr, const struct ethtool_rxnfc * rxnfc, size_t size, const u32 * rule_buf)
```

```json
{
  "name": "ethtool_rxnfc_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594392624,
      "name": "ethtool_rxnfc_copy_to_user",
      "external": false,
      "loc": "net/ethtool/ioctl.c:910",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_get_rxnfc",
        "net/ethtool/ioctl.c:ethtool_set_rxnfc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594392624,
      "name": "ethtool_rxnfc_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int ethtool_rxnfc_copy_to_user(void * useraddr, const struct ethtool_rxnfc * rxnfc, size_t size, const u32 * rule_buf)
```

```json
{
  "name": "ethtool_rxnfc_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595193888,
      "name": "ethtool_rxnfc_copy_to_user",
      "external": false,
      "loc": "net/ethtool/ioctl.c:945",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_get_rxnfc",
        "net/ethtool/ioctl.c:ethtool_set_rxnfc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595193888,
      "name": "ethtool_rxnfc_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int ethtool_rxnfc_copy_to_user(void * useraddr, const struct ethtool_rxnfc * rxnfc, size_t size, const u32 * rule_buf)
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
