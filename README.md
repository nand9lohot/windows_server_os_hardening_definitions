# Windows Server OS Hardening Definitions

This repository contains a **Chef library cookbook providing reusable CIS security control definitions** used by the `windows_server_os_hardening` cookbook.

The cookbook acts as a **shared definitions layer**, encapsulating CIS control implementations into modular components that can be reused across hardening recipes.

This design promotes **maintainability, modularity, and consistency** when enforcing Windows Server security baselines aligned with **CIS Benchmarks**.

---

## Overview

The `windows_server_os_hardening` project implements security hardening controls recommended by the **Center for Internet Security (CIS)**.

To keep the hardening logic clean and maintainable, the individual CIS control implementations are defined in this **library cookbook**. These definitions are then imported and executed by the primary hardening cookbook.

This separation provides:

- Reusable control definitions
- Consistent control implementation
- Simplified hardening recipes
- Easier updates when CIS benchmarks change
