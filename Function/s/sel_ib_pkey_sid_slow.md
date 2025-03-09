# Function: <code>sel_ib_pkey_sid_slow</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582713341,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:140",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582869149,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:140",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583067310,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:140",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583180830,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:140",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583368383,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583474335,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sel_ib_pkey_sid_slow(u64 subnet_prefix, u16 pkey_num, u32 * sid)
```

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897600,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897600,
      "name": "sel_ib_pkey_sid_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sel_ib_pkey_sid_slow(u64 subnet_prefix, u16 pkey_num, u32 * sid)
```

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017680,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017680,
      "name": "sel_ib_pkey_sid_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584045822,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:129",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584417026,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:129",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585044888,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:129",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585764104,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:129",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585994699,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:129",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586242043,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:129",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495238324,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228620560,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289203920,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274464794,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583443071,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583380143,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583426847,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sel_ib_pkey_sid_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583523086,
      "name": "sel_ib_pkey_sid_slow",
      "external": false,
      "loc": "security/selinux/ibpkey.c:130",
      "file": "security/selinux/ibpkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sel_ib_pkey_sid_slow(u64 subnet_prefix, u16 pkey_num, u32 * sid)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int sel_ib_pkey_sid_slow(u64 subnet_prefix, u16 pkey_num, u32 * sid)
```
</details>
</li>
</ul>
