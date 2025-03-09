# Function: <code>eeprom_fallback</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eeprom_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589862864,
      "name": "eeprom_fallback",
      "external": false,
      "loc": "net/ethtool/eeprom.c:53",
      "file": "net/ethtool/eeprom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589862864,
      "name": "eeprom_fallback.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eeprom_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590623744,
      "name": "eeprom_fallback",
      "external": false,
      "loc": "net/ethtool/eeprom.c:53",
      "file": "net/ethtool/eeprom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590623744,
      "name": "eeprom_fallback.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eeprom_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592245824,
      "name": "eeprom_fallback",
      "external": false,
      "loc": "net/ethtool/eeprom.c:53",
      "file": "net/ethtool/eeprom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592245824,
      "name": "eeprom_fallback.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eeprom_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594078464,
      "name": "eeprom_fallback",
      "external": false,
      "loc": "net/ethtool/eeprom.c:53",
      "file": "net/ethtool/eeprom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594078464,
      "name": "eeprom_fallback.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eeprom_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594457952,
      "name": "eeprom_fallback",
      "external": false,
      "loc": "net/ethtool/eeprom.c:53",
      "file": "net/ethtool/eeprom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594457952,
      "name": "eeprom_fallback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int eeprom_fallback(struct eeprom_req_info * request, struct eeprom_reply_data * reply)
```

```json
{
  "name": "eeprom_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595260224,
      "name": "eeprom_fallback",
      "external": false,
      "loc": "net/ethtool/eeprom.c:53",
      "file": "net/ethtool/eeprom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595260224,
      "name": "eeprom_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int eeprom_fallback(struct eeprom_req_info * request, struct eeprom_reply_data * reply)
```
</details>
</li>
</ul>
