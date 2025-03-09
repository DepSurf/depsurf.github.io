# Function: <code>nla_validate_range_unsigned</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585120944,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:162",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:nla_validate_int_range"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585001221,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:162",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:nla_validate_int_range"
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
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585442437,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:162",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:nla_validate_int_range"
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
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586583513,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:162",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:nla_validate_int_range"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int nla_validate_range_unsigned(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587823296,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:165",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823296,
      "name": "nla_validate_range_unsigned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
int nla_validate_range_unsigned(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094768,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:165",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094768,
      "name": "nla_validate_range_unsigned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int nla_validate_range_unsigned(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_range_unsigned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588430592,
      "name": "nla_validate_range_unsigned",
      "external": false,
      "loc": "lib/nlattr.c:170",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588430592,
      "name": "nla_validate_range_unsigned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int nla_validate_range_unsigned(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
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
