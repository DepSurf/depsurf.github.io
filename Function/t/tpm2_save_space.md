# Function: <code>tpm2_save_space</code>

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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584859886,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:446",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585278862,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:446",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585515896,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:450",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585635560,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:447",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585858568,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586001160,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
int tpm2_save_space(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738688,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:488",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738688,
      "name": "tpm2_save_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
int tpm2_save_space(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833168,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:488",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833168,
      "name": "tpm2_save_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586713365,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:488",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587263689,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588573417,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590028334,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590337614,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590679102,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498797988,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231412628,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291993660,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276300476,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585762136,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585621320,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585951176,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
  "name": "tpm2_save_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586058936,
      "name": "tpm2_save_space",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:483",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space"
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
int tpm2_save_space(struct tpm_chip * chip)
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
int tpm2_save_space(struct tpm_chip * chip)
```
</details>
</li>
</ul>
