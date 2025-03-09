# Function: <code>opal_save</code>

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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583434997,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2092",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583614901,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2104",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583830608,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2121",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583913736,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2121",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584094004,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2139",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584216676,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
int opal_save(struct opal_dev * dev, struct opal_lock_unlock * lk_unlk)
```

```json
{
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584600560,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2274",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:sed_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600560,
      "name": "opal_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int opal_save(struct opal_dev * dev, struct opal_lock_unlock * lk_unlk)
```

```json
{
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719408,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2274",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:sed_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719408,
      "name": "opal_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584755654,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2274",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585184356,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2274",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585921662,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2274",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586711996,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2340",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586974096,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2530",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587261768,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2718",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496074176,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229402860,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290330156,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275158094,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584185412,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584120660,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584169172,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
  "name": "opal_save",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584273556,
      "name": "opal_save",
      "external": false,
      "loc": "block/sed-opal.c:2159",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:sed_ioctl"
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
int opal_save(struct opal_dev * dev, struct opal_lock_unlock * lk_unlk)
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
int opal_save(struct opal_dev * dev, struct opal_lock_unlock * lk_unlk)
```
</details>
</li>
</ul>
