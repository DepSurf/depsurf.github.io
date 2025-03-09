# Function: <code>blake2s_update</code>

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
void blake2s_update(struct blake2s_state * state, const u8 * in, size_t inlen)
```

```json
{
  "name": "blake2s_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120384,
      "name": "blake2s_update",
      "external": true,
      "loc": "lib/crypto/blake2s.c:24",
      "file": "lib/crypto/blake2s.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120384,
      "name": "blake2s_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blake2s_update(struct blake2s_state * state, const u8 * in, size_t inlen)
```

```json
{
  "name": "blake2s_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587110320,
      "name": "blake2s_update",
      "external": true,
      "loc": "lib/crypto/blake2s.c:24",
      "file": "lib/crypto/blake2s.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110320,
      "name": "blake2s_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void blake2s_update(struct blake2s_state * state, const u8 * in, size_t inlen)
```

```json
{
  "name": "blake2s_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blake2s_update",
      "external": true,
      "loc": "lib/crypto/blake2s.c:24",
      "file": "lib/crypto/blake2s.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596642553,
      "name": "blake2s_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587372112,
      "name": "blake2s_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void blake2s_update(struct blake2s_state * state, const u8 * in, size_t inlen)
```

```json
{
  "name": "blake2s_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blake2s_update",
      "external": true,
      "loc": "lib/crypto/blake2s.c:24",
      "file": "lib/crypto/blake2s.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:add_timer_randomness",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:random_init_early",
        "drivers/char/random.c:add_bootloader_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597550805,
      "name": "blake2s_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587658896,
      "name": "blake2s_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void blake2s_update(struct blake2s_state * state, const u8 * in, size_t inlen)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
