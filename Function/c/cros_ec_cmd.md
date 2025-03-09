# Function: <code>cros_ec_cmd</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int cros_ec_cmd(struct cros_ec_device * ec_dev, unsigned int version, int command, void * outdata, size_t outsize, void * indata, size_t insize)
```

```json
{
  "name": "cros_ec_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592944912,
      "name": "cros_ec_cmd",
      "external": true,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:1004",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592944912,
      "name": "cros_ec_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int cros_ec_cmd(struct cros_ec_device * ec_dev, unsigned int version, int command, void * outdata, size_t outsize, void * indata, size_t insize)
```

```json
{
  "name": "cros_ec_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cros_ec_cmd",
      "external": true,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:1004",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596848744,
      "name": "cros_ec_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071593394688,
      "name": "cros_ec_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int cros_ec_cmd(struct cros_ec_device * ec_dev, unsigned int version, int command, const void * outdata, size_t outsize, void * indata, size_t insize)
```

```json
{
  "name": "cros_ec_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594140176,
      "name": "cros_ec_cmd",
      "external": true,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:1004",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594140176,
      "name": "cros_ec_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int cros_ec_cmd(struct cros_ec_device * ec_dev, unsigned int version, int command, void * outdata, size_t outsize, void * indata, size_t insize)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * outdata</code> ➡️ <code>const void * outdata</code>
</li>
</ul>
</details>
</li>
</ul>
