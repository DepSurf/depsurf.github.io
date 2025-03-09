# Function: <code>vcap_decode_actionset</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int vcap_decode_actionset(struct vcap_rule_internal * ri)
```

```json
{
  "name": "vcap_decode_actionset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591396560,
      "name": "vcap_decode_actionset",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:1221",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591396560,
      "name": "vcap_decode_actionset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
int vcap_decode_actionset(struct vcap_rule_internal * ri)
```

```json
{
  "name": "vcap_decode_actionset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591806528,
      "name": "vcap_decode_actionset",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:1417",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_disable",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591806528,
      "name": "vcap_decode_actionset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
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
int vcap_decode_actionset(struct vcap_rule_internal * ri)
```

```json
{
  "name": "vcap_decode_actionset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592554304,
      "name": "vcap_decode_actionset",
      "external": false,
      "loc": "drivers/net/ethernet/microchip/vcap/vcap_api.c:1431",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_disable",
        "drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592554304,
      "name": "vcap_decode_actionset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1098
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
int vcap_decode_actionset(struct vcap_rule_internal * ri)
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
