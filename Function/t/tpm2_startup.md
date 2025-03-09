# Function: <code>tpm2_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm2_startup(struct tpm_chip * chip, u16 startup_type)
```

```json
{
  "name": "tpm2_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242608,
      "name": "tpm2_startup",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:731",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242608,
      "name": "tpm2_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584583664,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:731",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583664,
      "name": "tpm2_startup.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584765200,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:761",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765200,
      "name": "tpm2_startup.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585632982,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:960",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585856076,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:996",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585998668,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586736540,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:697",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591470757,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:697",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591412024,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:698",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592463969,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:698",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594333911,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:707",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590024860,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:707",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590334152,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:707",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590675592,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:707",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498794912,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231409572,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291989080,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276295744,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585759644,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585618828,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585948684,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_startup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586056444,
      "name": "tpm2_startup",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1002",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int tpm2_startup(struct tpm_chip * chip, u16 startup_type)
```
</details>
</li>
</ul>
