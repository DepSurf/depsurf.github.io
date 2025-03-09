# Function: <code>pse_controller_unregister</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pse_controller_unregister(struct pse_controller_dev * pcdev)
```

```json
{
  "name": "pse_controller_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591338404,
      "name": "pse_controller_unregister",
      "external": true,
      "loc": "drivers/net/pse-pd/pse_core.c:92",
      "file": "drivers/net/pse-pd/pse_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/pse-pd/pse_core.c:devm_pse_controller_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337760,
      "name": "pse_controller_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pse_controller_unregister(struct pse_controller_dev * pcdev)
```

```json
{
  "name": "pse_controller_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591699924,
      "name": "pse_controller_unregister",
      "external": true,
      "loc": "drivers/net/pse-pd/pse_core.c:92",
      "file": "drivers/net/pse-pd/pse_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/pse-pd/pse_core.c:devm_pse_controller_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591699280,
      "name": "pse_controller_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pse_controller_unregister(struct pse_controller_dev * pcdev)
```

```json
{
  "name": "pse_controller_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592443028,
      "name": "pse_controller_unregister",
      "external": true,
      "loc": "drivers/net/pse-pd/pse_core.c:92",
      "file": "drivers/net/pse-pd/pse_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/pse-pd/pse_core.c:devm_pse_controller_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592442384,
      "name": "pse_controller_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void pse_controller_unregister(struct pse_controller_dev * pcdev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
