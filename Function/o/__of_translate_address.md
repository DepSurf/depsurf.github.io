# Function: <code>__of_translate_address</code>

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
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```

```json
{
  "name": "__of_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501638096,
      "name": "__of_translate_address",
      "external": false,
      "loc": "drivers/of/address.c:571",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_translate_dma_address",
        "drivers/of/address.c:of_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501638096,
      "name": "__of_translate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
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
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```

```json
{
  "name": "__of_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234157900,
      "name": "__of_translate_address",
      "external": false,
      "loc": "drivers/of/address.c:571",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_translate_dma_address",
        "drivers/of/address.c:of_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234157900,
      "name": "__of_translate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
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
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```

```json
{
  "name": "__of_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295073152,
      "name": "__of_translate_address",
      "external": false,
      "loc": "drivers/of/address.c:571",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_translate_dma_address",
        "drivers/of/address.c:of_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295073152,
      "name": "__of_translate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1952
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
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```

```json
{
  "name": "__of_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278097964,
      "name": "__of_translate_address",
      "external": false,
      "loc": "drivers/of/address.c:571",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_translate_dma_address",
        "drivers/of/address.c:of_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278097964,
      "name": "__of_translate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
u64 __of_translate_address(struct device_node * dev, struct device_node * (*)(const struct device_node *) get_parent, const __be32 * in_addr, const char * rprop, struct device_node * * host)
```
</details>
</li>
</ul>
