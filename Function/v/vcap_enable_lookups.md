# Function: <code>vcap_enable_lookups</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vcap_enable_lookups(struct vcap_control * vctrl, struct net_device * ndev, int chain_id, long unsigned int cookie, bool enable)
```

```json
{
  "name": "vcap_enable_lookups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591400720,
      "name": "vcap_enable_lookups",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:2630",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591400720,
      "name": "vcap_enable_lookups.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071591401264,
      "name": "vcap_enable_lookups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vcap_enable_lookups(struct vcap_control * vctrl, struct net_device * ndev, int src_cid, int dst_cid, long unsigned int cookie, bool enable)
```

```json
{
  "name": "vcap_enable_lookups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591813952,
      "name": "vcap_enable_lookups",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:3170",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591813952,
      "name": "vcap_enable_lookups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vcap_enable_lookups(struct vcap_control * vctrl, struct net_device * ndev, int src_cid, int dst_cid, long unsigned int cookie, bool enable)
```

```json
{
  "name": "vcap_enable_lookups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592561824,
      "name": "vcap_enable_lookups",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:3184",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592561824,
      "name": "vcap_enable_lookups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int vcap_enable_lookups(struct vcap_control * vctrl, struct net_device * ndev, int chain_id, long unsigned int cookie, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int src_cid</code>
</li>
<li>
<b>Param added. </b>
<code>int dst_cid</code>
</li>
<li>
<b>Param removed. </b>
<code>int chain_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>vctrl, ndev, chain_id, cookie, enable</code> ➡️ <code>vctrl, ndev, src_cid, dst_cid, cookie, enable</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
