# Function: <code>sk_filter_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586392827,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:902",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586833435,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:926",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587024507,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:928",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587152555,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:946",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587641952,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:965",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641952,
      "name": "sk_filter_release",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587960304,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1174",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960304,
      "name": "sk_filter_release",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588110640,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588110640,
      "name": "sk_filter_release",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588435840,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435840,
      "name": "sk_filter_release",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641712,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588641712,
      "name": "sk_filter_release",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589536653,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1165",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589545677,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1195",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
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
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589443385,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1195",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
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
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590178329,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1196",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
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
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591740634,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1197",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge",
        "net/core/filter.c:sk_filter_uncharge"
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
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593529994,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1199",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge",
        "net/core/filter.c:sk_filter_uncharge"
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
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593995590,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1199",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge",
        "net/core/filter.c:sk_filter_uncharge"
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
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594779834,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1204",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge",
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502180176,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502180176,
      "name": "sk_filter_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234925688,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234925688,
      "name": "sk_filter_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295653872,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295653872,
      "name": "sk_filter_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278468726,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588248448,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248448,
      "name": "sk_filter_release",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587961264,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961264,
      "name": "sk_filter_release",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588580272,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580272,
      "name": "sk_filter_release",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```

```json
{
  "name": "sk_filter_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588717760,
      "name": "sk_filter_release",
      "external": false,
      "loc": "net/core/filter.c:1176",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717760,
      "name": "sk_filter_release",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sk_filter_release(struct sk_filter * fp)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
