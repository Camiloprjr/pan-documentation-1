---
title: Token Wrapping Mechanism
sidebar_position: 3
---

The wrap function is a method used to convert PAN tokens into another token and vice-versa. To mint PAN tokens, the platform must burn SCB tokens, whereas burning PAN tokens leads the system to mint StableColb (SCB).

When doing the wrap mint, PAN’s system will show the availability of SCB that can be “converted” into PAN tokens. The minter selects the amount to be processed and chooses the transaction fee. This process can only be carried out in case the backoffice wallet has a balance in MATIC.

When doing the unwrap burn, PAN’s system will show the availability of PAN tokens that can be “converted” into SCB. The burner selects the amount to be processed and chooses the transaction fee. Likewise, this process can only be carried out in case the backoffice wallet has a balance in MATIC. 

![PAN](/img/colb.png)