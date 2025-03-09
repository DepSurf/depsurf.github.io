# Function: <code>_copy_mc_to_iter</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774080,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:728",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774080,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584790736,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:751",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790736,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2011
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585235248,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:698",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585235248,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1627
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
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:750",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127332,
      "name": "_copy_mc_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586067520,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:609",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596114757,
      "name": "_copy_mc_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071587060512,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:359",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596639801,
      "name": "_copy_mc_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587310080,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_mc_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_mc_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:234",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548112,
      "name": "_copy_mc_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587590688,
      "name": "_copy_mc_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1323
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
size_t _copy_mc_to_iter(const void * addr, size_t bytes, struct iov_iter * i)
```
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
