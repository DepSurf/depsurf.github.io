# Function: <code>tpm2_load_cmd</code>

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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584768669,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:549",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584851805,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:588",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585271293,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:588",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585508285,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:585",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585631037,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:526",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585853355,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585995931,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708352,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:176",
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
      "addr": 18446744071583708352,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583829088,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:183",
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
      "addr": 18446744071583829088,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854064,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:360",
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
      "addr": 18446744071583854064,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217296,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:360",
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
      "addr": 18446744071584217296,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584821136,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:360",
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
      "addr": 18446744071584821136,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520656,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:360",
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
      "addr": 18446744071585520656,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585752400,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:360",
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
      "addr": 18446744071585752400,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
```

```json
{
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585999824,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm2.c:360",
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
      "addr": 18446744071585999824,
      "name": "tpm2_load_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498792096,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231406596,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291986228,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276292606,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585756907,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585616091,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585945947,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
  "name": "tpm2_load_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586053755,
      "name": "tpm2_load_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:533",
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
int tpm2_load_cmd(struct tpm_chip * chip, struct trusted_key_payload * payload, struct trusted_key_options * options, u32 * blob_handle)
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
