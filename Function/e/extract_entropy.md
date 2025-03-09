# Function: <code>extract_entropy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t extract_entropy(struct entropy_store * r, void * buf, size_t nbytes, int min, int reserved)
```

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584165952,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1153",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165952,
      "name": "extract_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ssize_t extract_entropy(struct entropy_store * r, void * buf, size_t nbytes, int min, int reserved)
```

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509808,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1423",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509808,
      "name": "extract_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t extract_entropy(struct entropy_store * r, void * buf, size_t nbytes, int min, int reserved)
```

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584691920,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1423",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584691920,
      "name": "extract_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584774240,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1403",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774240,
      "name": "extract_entropy.constprop.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585194336,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1402",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194336,
      "name": "extract_entropy.constprop.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430560,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1506",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430560,
      "name": "extract_entropy.constprop.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585554624,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1515",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554624,
      "name": "extract_entropy.constprop.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774448,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774448,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585917088,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917088,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586652624,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1487",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652624,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586763360,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1486",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763360,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586644576,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1462",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:crng_reseed"
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587191876,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1482",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:crng_reseed"
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588496288,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:591",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_credit_init_bits",
        "drivers/char/random.c:crng_make_state",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496288,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589933296,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:651",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:crng_make_state",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589933296,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590243104,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:651",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:crng_make_state",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590243104,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590584128,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:651",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:crng_make_state",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590584128,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498738712,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498738712,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231358860,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231358860,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291890208,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291890208,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276246372,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276246372,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
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
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585678096,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678096,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585537936,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537936,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585867488,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867488,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585975264,
      "name": "extract_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1592",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975264,
      "name": "extract_entropy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t extract_entropy(struct entropy_store * r, void * buf, size_t nbytes, int min, int reserved)
```
</details>
</li>
</ul>
