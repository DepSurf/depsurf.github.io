# Function: <code>of_phandle_iterator_init</code>

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
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```

```json
{
  "name": "of_phandle_iterator_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501595992,
      "name": "of_phandle_iterator_init",
      "external": true,
      "loc": "drivers/of/base.c:1278",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/arm-smmu.c:__find_legacy_master_phandle",
        "drivers/of/base.c:__of_parse_phandle_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501595992,
      "name": "of_phandle_iterator_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```

```json
{
  "name": "of_phandle_iterator_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234122796,
      "name": "of_phandle_iterator_init",
      "external": true,
      "loc": "drivers/of/base.c:1278",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:__of_parse_phandle_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234122796,
      "name": "of_phandle_iterator_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```

```json
{
  "name": "of_phandle_iterator_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295016976,
      "name": "of_phandle_iterator_init",
      "external": true,
      "loc": "drivers/of/base.c:1278",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:__of_parse_phandle_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295016976,
      "name": "of_phandle_iterator_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```

```json
{
  "name": "of_phandle_iterator_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278064906,
      "name": "of_phandle_iterator_init",
      "external": true,
      "loc": "drivers/of/base.c:1278",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:__of_parse_phandle_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278064906,
      "name": "of_phandle_iterator_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_phandle_iterator_init(struct of_phandle_iterator * it, const struct device_node * np, const char * list_name, const char * cells_name, int cell_count)
```
</details>
</li>
</ul>
