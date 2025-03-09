# Function: <code>__of_changeset_apply_notify</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```

```json
{
  "name": "__of_changeset_apply_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501630328,
      "name": "__of_changeset_apply_notify",
      "external": true,
      "loc": "drivers/of/dynamic.c:736",
      "file": "drivers/of/dynamic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/dynamic.c:of_changeset_apply",
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501630328,
      "name": "__of_changeset_apply_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```

```json
{
  "name": "__of_changeset_apply_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234151424,
      "name": "__of_changeset_apply_notify",
      "external": true,
      "loc": "drivers/of/dynamic.c:736",
      "file": "drivers/of/dynamic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/dynamic.c:of_changeset_apply",
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234151424,
      "name": "__of_changeset_apply_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```

```json
{
  "name": "__of_changeset_apply_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295062704,
      "name": "__of_changeset_apply_notify",
      "external": true,
      "loc": "drivers/of/dynamic.c:736",
      "file": "drivers/of/dynamic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/dynamic.c:of_changeset_apply",
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295062704,
      "name": "__of_changeset_apply_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```

```json
{
  "name": "__of_changeset_apply_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278090680,
      "name": "__of_changeset_apply_notify",
      "external": true,
      "loc": "drivers/of/dynamic.c:736",
      "file": "drivers/of/dynamic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/dynamic.c:of_changeset_apply",
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278090680,
      "name": "__of_changeset_apply_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int __of_changeset_apply_notify(struct of_changeset * ocs)
```
</details>
</li>
</ul>
