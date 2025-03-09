# Function: <code>tpm2_get_cc_attrs_tbl</code>

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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584853393,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:1008",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585272807,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:983",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509813,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:965",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585632620,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:885",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585855372,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:922",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585997948,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586732544,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:618",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586732544,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586827264,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:618",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827264,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586707152,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:618",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707152,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587256928,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:618",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256928,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566272,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:627",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566272,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590020400,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:627",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590020400,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590329696,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:627",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590329696,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590671136,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:627",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590671136,
      "name": "tpm2_get_cc_attrs_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498794264,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231408924,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291989360,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276296072,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585758924,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585618108,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585947964,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
  "name": "tpm2_get_cc_attrs_tbl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586055740,
      "name": "tpm2_get_cc_attrs_tbl",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:924",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip * chip)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
