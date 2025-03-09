# Struct: <code>mmc_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    void (*)(struct mmc_request *) done;
    struct mmc_host * host;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    void (*)(struct mmc_request *) done;
    struct mmc_host * host;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
    bool crypto_enabled;
    int crypto_key_slot;
    u32 data_unit_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
    const struct bio_crypt_ctx * crypto_ctx;
    int crypto_key_slot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
    const struct bio_crypt_ctx * crypto_ctx;
    int crypto_key_slot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
    const struct bio_crypt_ctx * crypto_ctx;
    int crypto_key_slot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
    const struct bio_crypt_ctx * crypto_ctx;
    int crypto_key_slot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
    const struct bio_crypt_ctx * crypto_ctx;
    int crypto_key_slot;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct completion cmd_completion</code>
</li>
<li>
<b>Field added. </b>
<code>bool cap_cmd_during_tfr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct mmc_request *) recovery_notifier</code>
</li>
<li>
<b>Field added. </b>
<code>int tag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool crypto_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>int crypto_key_slot</code>
</li>
<li>
<b>Field added. </b>
<code>u32 data_unit_num</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct bio_crypt_ctx * crypto_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>bool crypto_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 data_unit_num</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct mmc_request {
    struct mmc_command * sbc;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct mmc_command * stop;
    struct completion completion;
    struct completion cmd_completion;
    void (*)(struct mmc_request *) done;
    void (*)(struct mmc_request *) recovery_notifier;
    struct mmc_host * host;
    bool cap_cmd_during_tfr;
    int tag;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
