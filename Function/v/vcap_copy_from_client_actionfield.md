# Function: <code>vcap_copy_from_client_actionfield</code>

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
void vcap_copy_from_client_actionfield(struct vcap_rule * rule, struct vcap_client_actionfield * field, struct vcap_client_actionfield_data * data)
```

```json
{
  "name": "vcap_copy_from_client_actionfield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcap_copy_from_client_actionfield",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:2370",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_mod_action_u32",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387536,
      "name": "vcap_copy_from_client_actionfield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071596268088,
      "name": "vcap_copy_from_client_actionfield.cold",
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
void vcap_copy_from_client_actionfield(struct vcap_rule * rule, struct vcap_client_actionfield * dst, const struct vcap_client_actionfield * src)
```

```json
{
  "name": "vcap_copy_from_client_actionfield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcap_copy_from_client_actionfield",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:587",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591798224,
      "name": "vcap_copy_from_client_actionfield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071596797649,
      "name": "vcap_copy_from_client_actionfield.cold",
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
void vcap_copy_from_client_actionfield(struct vcap_rule * rule, struct vcap_client_actionfield * dst, const struct vcap_client_actionfield * src)
```

```json
{
  "name": "vcap_copy_from_client_actionfield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcap_copy_from_client_actionfield",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:587",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592545968,
      "name": "vcap_copy_from_client_actionfield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071597721255,
      "name": "vcap_copy_from_client_actionfield.cold",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void vcap_copy_from_client_actionfield(struct vcap_rule * rule, struct vcap_client_actionfield * field, struct vcap_client_actionfield_data * data)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vcap_client_actionfield * dst</code>
</li>
<li>
<b>Param added. </b>
<code>const struct vcap_client_actionfield * src</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vcap_client_actionfield * field</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vcap_client_actionfield_data * data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
