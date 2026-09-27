---
tempo-contracts: minor
---

Added the `V1ValidatorSetTooLarge` error to `IValidatorConfigV2`. The V2 migration now fails with it when the V1 validator count does not fit the `u8` migration index, instead of snapshotting a truncated count.
