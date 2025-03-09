# Function: <code>cec_pin_update</code>

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
void cec_pin_update(struct cec_pin * pin, bool v, bool force)
```

```json
{
  "name": "cec_pin_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500920160,
      "name": "cec_pin_update",
      "external": false,
      "loc": "drivers/media/cec/cec-pin.c:111",
      "file": "drivers/media/cec/cec-pin.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter",
        "drivers/media/cec/cec-pin.c:cec_pin_changed",
        "drivers/media/cec/cec-pin.c:cec_pin_low",
        "drivers/media/cec/cec-pin.c:cec_pin_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500920160,
      "name": "cec_pin_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cec_pin_update(struct cec_pin * pin, bool v, bool force)
```

```json
{
  "name": "cec_pin_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587805136,
      "name": "cec_pin_update",
      "external": false,
      "loc": "drivers/media/cec/cec-pin.c:111",
      "file": "drivers/media/cec/cec-pin.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter",
        "drivers/media/cec/cec-pin.c:cec_pin_changed",
        "drivers/media/cec/cec-pin.c:cec_pin_low",
        "drivers/media/cec/cec-pin.c:cec_pin_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805136,
      "name": "cec_pin_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void cec_pin_update(struct cec_pin * pin, bool v, bool force)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➕</summary>

```c
void cec_pin_update(struct cec_pin * pin, bool v, bool force)
```
</details>
</li>
</ul>
