# Function: <code>_credit_init_bits</code>

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
void _credit_init_bits(size_t bits)
```

```json
{
  "name": "_credit_init_bits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594323648,
      "name": "_credit_init_bits",
      "external": false,
      "loc": "drivers/char/random.c:635",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:entropy_timer",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594323648,
      "name": "_credit_init_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_credit_init_bits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589939511,
      "name": "_credit_init_bits",
      "external": false,
      "loc": "drivers/char/random.c:703",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589937920,
      "name": "_credit_init_bits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071596238062,
      "name": "_credit_init_bits.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_credit_init_bits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590248795,
      "name": "_credit_init_bits",
      "external": false,
      "loc": "drivers/char/random.c:703",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247200,
      "name": "_credit_init_bits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071596766262,
      "name": "_credit_init_bits.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "_credit_init_bits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590589796,
      "name": "_credit_init_bits",
      "external": false,
      "loc": "drivers/char/random.c:703",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590588224,
      "name": "_credit_init_bits.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071597674923,
      "name": "_credit_init_bits.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void _credit_init_bits(size_t bits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void _credit_init_bits(size_t bits)
```
</details>
</li>
</ul>
