# Function: <code>nla_validate_int_range</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584113920,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:98",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584301874,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584436598,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585000320,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:275",
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
      "addr": 18446744071585000320,
      "name": "nla_validate_int_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:302",
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
      "addr": 18446744071585120800,
      "name": "nla_validate_int_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071591380470,
      "name": "nla_validate_int_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:302",
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
      "addr": 18446744071585001072,
      "name": "nla_validate_int_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071591322858,
      "name": "nla_validate_int_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:302",
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
      "addr": 18446744071585442288,
      "name": "nla_validate_int_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071592336735,
      "name": "nla_validate_int_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```

```json
{
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:302",
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
      "addr": 18446744071586583424,
      "name": "nla_validate_int_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071594197198,
      "name": "nla_validate_int_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587825432,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:313",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588096930,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:313",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588432727,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:325",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496321880,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229656692,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290639568,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275374056,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584405334,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584340534,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584388246,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
  "name": "nla_validate_int_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584494310,
      "name": "nla_validate_int_range",
      "external": false,
      "loc": "lib/nlattr.c:99",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
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
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int validate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int nla_validate_int_range(const struct nla_policy * pt, const struct nlattr * nla, struct netlink_ext_ack * extack, unsigned int validate)
```
</details>
</li>
</ul>
