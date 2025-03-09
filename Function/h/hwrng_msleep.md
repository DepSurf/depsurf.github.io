# Function: <code>hwrng_msleep</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int hwrng_msleep(struct hwrng * rng, unsigned int msecs)
```

```json
{
  "name": "hwrng_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589970400,
      "name": "hwrng_msleep",
      "external": true,
      "loc": "drivers/char/hw_random/core.c:674",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967568,
      "name": "hwrng_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long int hwrng_msleep(struct hwrng * rng, unsigned int msecs)
```

```json
{
  "name": "hwrng_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590280000,
      "name": "hwrng_msleep",
      "external": true,
      "loc": "drivers/char/hw_random/core.c:674",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590277168,
      "name": "hwrng_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long int hwrng_msleep(struct hwrng * rng, unsigned int msecs)
```

```json
{
  "name": "hwrng_msleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590621104,
      "name": "hwrng_msleep",
      "external": true,
      "loc": "drivers/char/hw_random/core.c:681",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590618112,
      "name": "hwrng_msleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long int hwrng_msleep(struct hwrng * rng, unsigned int msecs)
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
