# Function: <code>blk_ksm_register</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager * ksm, struct request_queue * q)
```

```json
{
  "name": "blk_ksm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_ksm_register",
      "external": true,
      "loc": "block/keyslot-manager.c:382",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618358,
      "name": "blk_ksm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584616240,
      "name": "blk_ksm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool blk_ksm_register(struct blk_keyslot_manager * ksm, struct request_queue * q)
```

```json
{
  "name": "blk_ksm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_ksm_register",
      "external": true,
      "loc": "block/keyslot-manager.c:389",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378701,
      "name": "blk_ksm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584735056,
      "name": "blk_ksm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager * ksm, struct request_queue * q)
```

```json
{
  "name": "blk_ksm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_ksm_register",
      "external": true,
      "loc": "block/keyslot-manager.c:440",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/crypto.c:mmc_crypto_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320935,
      "name": "blk_ksm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584762720,
      "name": "blk_ksm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager * ksm, struct request_queue * q)
```

```json
{
  "name": "blk_ksm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_ksm_register",
      "external": true,
      "loc": "block/keyslot-manager.c:440",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/crypto.c:mmc_crypto_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592322536,
      "name": "blk_ksm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585191184,
      "name": "blk_ksm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager * ksm, struct request_queue * q)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool blk_ksm_register(struct blk_keyslot_manager * ksm, struct request_queue * q)
```
</details>
</li>
</ul>
