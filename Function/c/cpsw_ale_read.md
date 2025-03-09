# Function: <code>cpsw_ale_read</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int cpsw_ale_read(struct cpsw_ale * ale, int idx, u32 * ale_entry)
```

```json
{
  "name": "cpsw_ale_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232599028,
      "name": "cpsw_ale_read",
      "external": false,
      "loc": "drivers/net/ethernet/ti/cpsw_ale.c:140",
      "file": "drivers/net/ethernet/ti/cpsw_ale.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_dump",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_set_allmulti",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_del_vlan",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_vlan",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_del_mcast",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_mcast",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_mcast",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_flush_multicast",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_find_ageable",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_match_free",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_match_vlan",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232599028,
      "name": "cpsw_ale_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cpsw_ale_read(struct cpsw_ale * ale, int idx, u32 * ale_entry)
```
</details>
</li>
</ul>
