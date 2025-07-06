# Documentation Improvement

## 🖼️ Logo Inconsistency: Songbird Network (Chain ID 19)

In the Ethereum app, the Songbird network (Chain ID 19) displays inconsistent logos across different device types and icon sizes.

### ✅ Current Status

- `icons/flex_app_chain_19.gif` — ✅ Updated with the **new Songbird logo** (correct)
- `icons/stax_app_chain_19.gif` — ❌ Still shows the **old logo** (needs update)
- `icons/nanox_app_chain_19.gif` — ❌ Still shows the **old logo** (needs update)
- `glyphs/chain_19_14px.gif` — ❌ Still shows the **old logo** (needs update)
- `glyphs/chain_19_64px.gif` — ❌ Still shows the **old logo** (needs update)

### 🧭 Impact

This inconsistency causes a confusing user experience, especially when users switch between devices or views. A unified visual identity is important for user trust and clarity.

---

## 🧪 Testing Issues in `tests/ragger` (Ethereum App)

### 🚫 Current Limitations

- No clear way to test different screens interactively.
- Screens advance **too quickly**, with **no easy way to slow them down**.
- **QR code navigation** is not tested.
- No tests simulate **arrow-based UI navigation**.

See additional context: [PR #835](https://github.com/LedgerHQ/app-ethereum/pull/835)

### ❗ Failing or Inconsistent Tests (Using VSCode Extension: *Run tests with display*)

```plaintext
tests/ragger/test_eip7702.py::test_eip7702_in_whitelist[flex]                        FAILED  [ 10%]
tests/ragger/test_eip7702.py::test_eip7702_in_whitelist_all_chain_whitelisted[flex]  PASSED  [ 11%]
tests/ragger/test_eip7702.py::test_eip7702_in_whitelist_all_chain_param[flex]        FAILED  [ 11%]
tests/ragger/test_eip7702.py::test_eip7702_in_whitelist_max[flex]                    FAILED  [ 12%]