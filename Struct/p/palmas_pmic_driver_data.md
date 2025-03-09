# Struct: <code>palmas_pmic_driver_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
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
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct of_regulator_match * palmas_matches</code> ➡️ <code>struct of_regulator_match * palmas_matches</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct of_regulator_match * palmas_matches</code> ➡️ <code>struct of_regulator_match * palmas_matches</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct of_regulator_match * palmas_matches</code> ➡️ <code>struct of_regulator_match * palmas_matches</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct of_regulator_match * palmas_matches</code> ➡️ <code>struct of_regulator_match * palmas_matches</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct palmas_pmic_driver_data {
    int smps_start;
    int smps_end;
    int ldo_begin;
    int ldo_end;
    int max_reg;
    bool has_regen3;
    struct palmas_regs_info * palmas_regs_info;
    struct of_regulator_match * palmas_matches;
    struct palmas_sleep_requestor_info * sleep_req_info;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) smps_register;
    int (*)(struct palmas_pmic *, struct palmas_pmic_driver_data *, struct palmas_pmic_platform_data *, const char *, struct regulator_config) ldo_register;
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
