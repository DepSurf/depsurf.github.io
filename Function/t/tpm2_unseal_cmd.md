# Function: <code>tpm2_unseal_cmd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584769042,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:641",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584852276,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:654",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585271778,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:654",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585508668,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:651",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585631420,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:592",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585853726,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585996302,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583707920,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:240",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707920,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828656,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:247",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828656,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854720,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:458",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854720,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217952,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:458",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217952,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584821840,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:458",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821840,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521376,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:458",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521376,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753120,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:458",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753120,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
```

```json
{
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000544,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:458",
      "file": "security/keys/trusted-keys/trusted_tpm2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000544,
      "name": "tpm2_unseal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498792480,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231406992,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291986700,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276293312,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585757278,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585616462,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585946318,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
  "name": "tpm2_unseal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586054123,
      "name": "tpm2_unseal_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:597",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
int tpm2_unseal_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 blob_handle)
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
