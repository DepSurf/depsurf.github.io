# Function: <code>vcap_erase_cache</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vcap_erase_cache(struct vcap_rule_internal * ri)
```

```json
{
  "name": "vcap_erase_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591400553,
      "name": "vcap_erase_cache",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:749",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_mod_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_read_rule"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402704,
      "name": "vcap_erase_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void vcap_erase_cache(struct vcap_rule_internal * ri)
```

```json
{
  "name": "vcap_erase_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591813458,
      "name": "vcap_erase_cache",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:878",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_mod_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_add_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_read_rule"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591815328,
      "name": "vcap_erase_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void vcap_erase_cache(struct vcap_rule_internal * ri)
```

```json
{
  "name": "vcap_erase_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592561329,
      "name": "vcap_erase_cache",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:878",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_enable",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_mod_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_add_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_read_rule"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592563232,
      "name": "vcap_erase_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void vcap_erase_cache(struct vcap_rule_internal * ri)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
