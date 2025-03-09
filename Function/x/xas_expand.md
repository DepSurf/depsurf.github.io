# Function: <code>xas_expand</code>

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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589429786,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:539",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589887201,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:554",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590113153,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
int xas_expand(struct xa_state * xas, void * head)
```

```json
{
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585113744,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585113744,
      "name": "xas_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int xas_expand(struct xa_state * xas, void * head)
```

```json
{
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263248,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263248,
      "name": "xas_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585146080,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:558",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146080,
      "name": "xas_expand.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:558",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585596976,
      "name": "xas_expand.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071592344908,
      "name": "xas_expand.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:561",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756912,
      "name": "xas_expand.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
    },
    {
      "addr": 18446744071594206941,
      "name": "xas_expand.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:561",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595920992,
      "name": "xas_expand.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071596375722,
      "name": "xas_expand.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:559",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596439312,
      "name": "xas_expand.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    },
    {
      "addr": 18446744071596905214,
      "name": "xas_expand.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:559",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xas_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597334672,
      "name": "xas_expand.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    },
    {
      "addr": 18446744071597830307,
      "name": "xas_expand.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503894392,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236523852,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297762752,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279780136,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589715409,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589441185,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590158785,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
  "name": "xas_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590209425,
      "name": "xas_expand",
      "external": false,
      "loc": "lib/xarray.c:555",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create"
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
int xas_expand(struct xa_state * xas, void * head)
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
int xas_expand(struct xa_state * xas, void * head)
```
</details>
</li>
</ul>
