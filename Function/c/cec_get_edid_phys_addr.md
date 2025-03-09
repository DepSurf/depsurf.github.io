# Function: <code>cec_get_edid_phys_addr</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587248832,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:65",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248832,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587516480,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516480,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719456,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719456,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500896312,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500896312,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233415036,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233415036,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294351312,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294351312,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277675546,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277675546,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587360400,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360400,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128624,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128624,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587675600,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587675600,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```

```json
{
  "name": "cec_get_edid_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587781984,
      "name": "cec_get_edid_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:68",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587781984,
      "name": "cec_get_edid_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
```
</details>
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
u16 cec_get_edid_phys_addr(const u8 * edid, unsigned int size, unsigned int * offset)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
