# Function: <code>i2c_nuvoton_wait_for_stat</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int i2c_nuvoton_wait_for_stat(struct tpm_chip * chip, u8 mask, u8 value, u32 timeout, wait_queue_head_t * queue)
```

```json
{
  "name": "i2c_nuvoton_wait_for_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292023024,
      "name": "i2c_nuvoton_wait_for_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_i2c_nuvoton.c:170",
      "file": "drivers/char/tpm/tpm_i2c_nuvoton.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_send",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_send",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_send",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_send",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_recv",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_recv",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292023024,
      "name": "i2c_nuvoton_wait_for_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int i2c_nuvoton_wait_for_stat(struct tpm_chip * chip, u8 mask, u8 value, u32 timeout, wait_queue_head_t * queue)
```
</details>
</li>
</ul>
