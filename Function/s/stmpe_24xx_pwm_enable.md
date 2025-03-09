# Function: <code>stmpe_24xx_pwm_enable</code>

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
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```

```json
{
  "name": "stmpe_24xx_pwm_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496815984,
      "name": "stmpe_24xx_pwm_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-stmpe.c:39",
      "file": "drivers/pwm/pwm-stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config",
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496815984,
      "name": "stmpe_24xx_pwm_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```

```json
{
  "name": "stmpe_24xx_pwm_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230099348,
      "name": "stmpe_24xx_pwm_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-stmpe.c:39",
      "file": "drivers/pwm/pwm-stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config",
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230099348,
      "name": "stmpe_24xx_pwm_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```

```json
{
  "name": "stmpe_24xx_pwm_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290886832,
      "name": "stmpe_24xx_pwm_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-stmpe.c:39",
      "file": "drivers/pwm/pwm-stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config",
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290886832,
      "name": "stmpe_24xx_pwm_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```

```json
{
  "name": "stmpe_24xx_pwm_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275526084,
      "name": "stmpe_24xx_pwm_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-stmpe.c:39",
      "file": "drivers/pwm/pwm-stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config",
        "drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275526084,
      "name": "stmpe_24xx_pwm_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int stmpe_24xx_pwm_enable(struct pwm_chip * chip, struct pwm_device * pwm)
```
</details>
</li>
</ul>
