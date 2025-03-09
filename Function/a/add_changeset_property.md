# Function: <code>add_changeset_property</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "add_changeset_property",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501656880,
      "name": "add_changeset_property",
      "external": false,
      "loc": "drivers/of/overlay.c:302",
      "file": "drivers/of/overlay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501656880,
      "name": "add_changeset_property.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int add_changeset_property(struct overlay_changeset * ovcs, struct target * target, struct property * overlay_prop, bool is_symbols_prop)
```

```json
{
  "name": "add_changeset_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234176668,
      "name": "add_changeset_property",
      "external": false,
      "loc": "drivers/of/overlay.c:302",
      "file": "drivers/of/overlay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234176668,
      "name": "add_changeset_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_changeset_property",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295102608,
      "name": "add_changeset_property",
      "external": false,
      "loc": "drivers/of/overlay.c:302",
      "file": "drivers/of/overlay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295102608,
      "name": "add_changeset_property.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_changeset_property",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278112442,
      "name": "add_changeset_property",
      "external": false,
      "loc": "drivers/of/overlay.c:302",
      "file": "drivers/of/overlay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/overlay.c:of_overlay_fdt_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278112442,
      "name": "add_changeset_property.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int add_changeset_property(struct overlay_changeset * ovcs, struct target * target, struct property * overlay_prop, bool is_symbols_prop)
```
</details>
</li>
</ul>
