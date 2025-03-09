# Function: <code>vcap_keyfieldset</code>

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
const struct vcap_set * vcap_keyfieldset(struct vcap_control * vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset)
```

```json
{
  "name": "vcap_keyfieldset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591398294,
      "name": "vcap_keyfieldset",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:405",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_set_rule_set_keyset",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_keyfield_typegroup",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591380256,
      "name": "vcap_keyfieldset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const struct vcap_set * vcap_keyfieldset(struct vcap_control * vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset)
```

```json
{
  "name": "vcap_keyfieldset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591795950,
      "name": "vcap_keyfieldset",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:407",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_select_min_rule_keyset",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_set_rule_set_keyset",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_keyfield_typegroup",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591786832,
      "name": "vcap_keyfieldset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const struct vcap_set * vcap_keyfieldset(struct vcap_control * vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset)
```

```json
{
  "name": "vcap_keyfieldset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592543694,
      "name": "vcap_keyfieldset",
      "external": true,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:407",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_select_min_rule_keyset",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_set_rule_set_keyset",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_keyfield_typegroup",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592534256,
      "name": "vcap_keyfieldset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const struct vcap_set * vcap_keyfieldset(struct vcap_control * vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset)
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
