# Function: <code>tpm2_load_space</code>

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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584859227,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:177",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585278203,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:177",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585515418,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:180",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585635082,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:178",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585858014,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586000606,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm2_load_space(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738432,
      "name": "tpm2_load_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071586740232,
      "name": "tpm2_load_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int tpm2_load_space(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832912,
      "name": "tpm2_load_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071591471183,
      "name": "tpm2_load_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586712781,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587262840,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588572552,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590027416,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590336696,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590678184,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:176",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498797288,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231412024,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291992768,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276299776,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585761582,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585620766,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585950622,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
  "name": "tpm2_load_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586058382,
      "name": "tpm2_load_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:173",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
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
int tpm2_load_space(struct tpm_chip * chip)
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
int tpm2_load_space(struct tpm_chip * chip)
```
</details>
</li>
</ul>
