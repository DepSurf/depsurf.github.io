# Function: <code>vcap_copy_to_client_keyfield</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void vcap_copy_to_client_keyfield(struct vcap_rule_internal * ri, struct vcap_client_keyfield * field, u8 * value, u8 * mask, u16 width)
```

```json
{
  "name": "vcap_copy_to_client_keyfield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcap_copy_to_client_keyfield",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:990",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386832,
      "name": "vcap_copy_to_client_keyfield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071596268048,
      "name": "vcap_copy_to_client_keyfield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void vcap_copy_to_client_keyfield(struct vcap_rule_internal * ri, struct vcap_client_keyfield * field, u8 * value, u8 * mask, u16 width)
```

```json
{
  "name": "vcap_copy_to_client_keyfield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcap_copy_to_client_keyfield",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:1186",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591797520,
      "name": "vcap_copy_to_client_keyfield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071596797610,
      "name": "vcap_copy_to_client_keyfield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void vcap_copy_to_client_keyfield(struct vcap_rule_internal * ri, struct vcap_client_keyfield * field, u8 * value, u8 * mask, u16 width)
```

```json
{
  "name": "vcap_copy_to_client_keyfield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcap_copy_to_client_keyfield",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:1200",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592545264,
      "name": "vcap_copy_to_client_keyfield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071597721216,
      "name": "vcap_copy_to_client_keyfield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void vcap_copy_to_client_keyfield(struct vcap_rule_internal * ri, struct vcap_client_keyfield * field, u8 * value, u8 * mask, u16 width)
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
