# Function: <code>trust_moklist</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool trust_moklist()
```

```json
{
  "name": "trust_moklist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617237507,
      "name": "trust_moklist",
      "external": true,
      "loc": "security/integrity/platform_certs/machine_keyring.c:65",
      "file": "security/integrity/platform_certs/machine_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617237507,
      "name": "trust_moklist",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool trust_moklist()
```

```json
{
  "name": "trust_moklist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627951376,
      "name": "trust_moklist",
      "external": true,
      "loc": "security/integrity/platform_certs/machine_keyring.c:65",
      "file": "security/integrity/platform_certs/machine_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627951376,
      "name": "trust_moklist",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool trust_moklist()
```

```json
{
  "name": "trust_moklist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619714672,
      "name": "trust_moklist",
      "external": true,
      "loc": "security/integrity/platform_certs/machine_keyring.c:65",
      "file": "security/integrity/platform_certs/machine_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619714672,
      "name": "trust_moklist",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trust_moklist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622021982,
      "name": "trust_moklist",
      "external": false,
      "loc": "security/integrity/platform_certs/machine_keyring.c:64",
      "file": "security/integrity/platform_certs/machine_keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/platform_certs/machine_keyring.c:imputed_trust_enabled"
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
bool trust_moklist()
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool trust_moklist()
```
</details>
</li>
</ul>
