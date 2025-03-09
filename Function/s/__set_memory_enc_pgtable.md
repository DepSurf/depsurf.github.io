# Function: <code>__set_memory_enc_pgtable</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc)
```

```json
{
  "name": "__set_memory_enc_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_memory_enc_pgtable",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2024",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576992,
      "name": "__set_memory_enc_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071593855434,
      "name": "__set_memory_enc_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc)
```

```json
{
  "name": "__set_memory_enc_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_memory_enc_pgtable",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2128",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685984,
      "name": "__set_memory_enc_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071595970192,
      "name": "__set_memory_enc_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc)
```

```json
{
  "name": "__set_memory_enc_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_memory_enc_pgtable",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2129",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699856,
      "name": "__set_memory_enc_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071596487783,
      "name": "__set_memory_enc_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc)
```

```json
{
  "name": "__set_memory_enc_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_memory_enc_pgtable",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2133",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734384,
      "name": "__set_memory_enc_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071597384405,
      "name": "__set_memory_enc_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc)
```
</details>
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
