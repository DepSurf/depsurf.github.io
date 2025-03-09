# Function: <code>vcap_set_bit</code>

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
void vcap_set_bit(u32 * stream, struct vcap_stream_iter * itr, bool value)
```

```json
{
  "name": "vcap_set_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591386024,
      "name": "vcap_set_bit",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:95",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field"
      ],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381440,
      "name": "vcap_set_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071596267599,
      "name": "vcap_set_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void vcap_set_bit(u32 * stream, struct vcap_stream_iter * itr, bool value)
```

```json
{
  "name": "vcap_set_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591800735,
      "name": "vcap_set_bit",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:97",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field"
      ],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591788096,
      "name": "vcap_set_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071596797359,
      "name": "vcap_set_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void vcap_set_bit(u32 * stream, struct vcap_stream_iter * itr, bool value)
```

```json
{
  "name": "vcap_set_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592548479,
      "name": "vcap_set_bit",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:97",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field"
      ],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592535520,
      "name": "vcap_set_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071597720965,
      "name": "vcap_set_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void vcap_set_bit(u32 * stream, struct vcap_stream_iter * itr, bool value)
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
