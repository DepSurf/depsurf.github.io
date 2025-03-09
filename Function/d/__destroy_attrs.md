# Function: <code>__destroy_attrs</code>

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
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590964359,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1353",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
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
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590894959,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1537",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591729279,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1602",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": [
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591723376,
      "name": "__destroy_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593431167,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1602",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": [
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593424496,
      "name": "__destroy_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595345231,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1929",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": [
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595337216,
      "name": "__destroy_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595740735,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:2256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": [
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595732288,
      "name": "__destroy_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "__destroy_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596588575,
      "name": "__destroy_attrs",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:2319",
      "file": "net/ipv6/seg6_local.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:seg6_local_destroy_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state"
      ],
      "caller_func": [
        "net/ipv6/seg6_local.c:parse_nla_action",
        "net/ipv6/seg6_local.c:parse_nla_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596580096,
      "name": "__destroy_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt * slwt)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
