---
'@rainbow-me/rainbowkit': patch
---

The wagmi peer dependency has been updated to minimum `0.11.6`.

Added `safeWallet` connector to support Safe Apps. dApps that rely on `getDefaultWallets` will adopt this behavior automatically. dApps that rely on the Custom Wallet List should add `safeWallet` alongside `injectedWallet`.
