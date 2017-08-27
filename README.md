
# CORION platform
Ethereum contract based multifunctional platform.

## Our contacts
Website:
https://www.corion.io

Email:
contact@corion.io

Bitcoin Talk:
https://bitcointalk.org/index.php?topic=1920823.0

Slack:
https://corionplatform.slack.com/shared_invite/MTg0MDIwNjM1NTIxLTE0OTUwMjE5MjEtNDcxYTdlZGUxYg

## Contract on the Ethereum Classic blockchain

### Token
Address:
```
0xc1FD237D844C0A1A4F18A5d6bd44F57dF48E5e6A
```

ABI:
```javascript
[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"name":"value","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"isActive","outputs":[{"name":"success","type":"bool"},{"name":"active","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"from","type":"address"},{"name":"to","type":"address"},{"name":"amount","type":"uint256"}],"name":"transferFrom","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"moduleHandlerAddress","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"owner","type":"address"},{"name":"value","type":"uint256"}],"name":"processTransactionFee","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"spender","type":"address"},{"name":"amount","type":"uint256"},{"name":"nonce","type":"uint256"},{"name":"extraData","type":"bytes"}],"name":"approveAndCall","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"transactionFeeMin","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"owner","type":"address"},{"name":"value","type":"uint256"}],"name":"mint","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"addr","type":"address"}],"name":"replaceModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"spender","type":"address"},{"name":"amount","type":"uint256"},{"name":"nonce","type":"uint256"}],"name":"approve","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"db","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"from","type":"address"},{"name":"to","type":"address"},{"name":"amount","type":"uint256"},{"name":"fee","type":"bool"}],"name":"transferFromByModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"disconnectModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"from","type":"address"},{"name":"to","type":"address"},{"name":"value","type":"uint256"}],"name":"transferEvent","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"roundID","type":"uint256"},{"name":"reward","type":"uint256"}],"name":"newSchellingRoundEvent","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"connectModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"owner","type":"address"}],"name":"balanceOf","outputs":[{"name":"value","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"transactionFeeMax","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"forever","type":"bool"}],"name":"disableModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"aType","type":"uint8"},{"name":"value","type":"uint256"},{"name":"addr","type":"address"}],"name":"configureModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"owner","type":"address"},{"name":"value","type":"uint256"}],"name":"burn","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"disabledUntil","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"to","type":"address"},{"name":"amount","type":"uint256"}],"name":"transfer","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"transactionFeeRate","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"moduleStatus","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"to","type":"address"},{"name":"amount","type":"uint256"},{"name":"extraData","type":"bytes"}],"name":"transfer","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"transactionFeeRateM","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"transactionFeeBurn","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"owner","type":"address"},{"name":"spender","type":"address"}],"name":"allowance","outputs":[{"name":"remaining","type":"uint256"},{"name":"nonce","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"value","type":"uint256"}],"name":"getTransactionFee","outputs":[{"name":"success","type":"bool"},{"name":"fee","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"newModuleHandlerAddress","type":"address"}],"name":"replaceModuleHandler","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"inputs":[{"name":"moduleHandlerAddr","type":"address"},{"name":"dbAddr","type":"address"}],"payable":false,"type":"constructor"},{"anonymous":false,"inputs":[{"indexed":true,"name":"spender","type":"address"},{"indexed":true,"name":"owner","type":"address"},{"indexed":true,"name":"value","type":"uint256"}],"name":"AllowanceUsed","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"addr","type":"address"},{"indexed":true,"name":"value","type":"uint256"}],"name":"Mint","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"addr","type":"address"},{"indexed":true,"name":"value","type":"uint256"}],"name":"Burn","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_owner","type":"address"},{"indexed":true,"name":"_spender","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Approval","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_from","type":"address"},{"indexed":true,"name":"_to","type":"address"},{"indexed":true,"name":"_value","type":"uint256"},{"indexed":false,"name":"_extraData","type":"bytes"}],"name":"Transfer","type":"event"}]
```

### Premium
Address:
```
0x452d5E21BD86bb419690827cC5AC024b6940040b
```

ABI:
```javascript
[{"constant":true,"inputs":[],"name":"isActive","outputs":[{"name":"success","type":"bool"},{"name":"active","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"moduleHandlerAddress","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"priv","type":"bool"},{"name":"name","type":"string"},{"name":"website","type":"string"},{"name":"country","type":"uint256"},{"name":"info","type":"string"},{"name":"rate","type":"uint8"},{"name":"isForRent","type":"bool"},{"name":"admin","type":"address"}],"name":"openProvider","outputs":[],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"providerUID","type":"uint256"},{"name":"name","type":"string"},{"name":"website","type":"string"},{"name":"country","type":"uint256"},{"name":"info","type":"string"},{"name":"rate","type":"uint8"},{"name":"admin","type":"address"}],"name":"setProviderDetails","outputs":[],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"addr","type":"address"}],"name":"replaceModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"providerUID","type":"uint256"},{"name":"invite","type":"address[]"},{"name":"revokeInvite","type":"address[]"}],"name":"manageInvitations","outputs":[],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"db","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"minFundsForPublic","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"interestMinFunds","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"beneficiary","type":"address"},{"name":"providerUID","type":"uint256"},{"name":"roundLimit","type":"uint256"}],"name":"getReward","outputs":[],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"disconnectModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"from","type":"address"},{"name":"to","type":"address"},{"name":"value","type":"uint256"}],"name":"transferEvent","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"roundID","type":"uint256"},{"name":"reward","type":"uint256"}],"name":"newSchellingRoundEvent","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"privateProviderLimit","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"connectModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"forever","type":"bool"}],"name":"disableModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"partProvider","outputs":[],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"publicMaxRate","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"closeProvider","outputs":[],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"minFundsForPrivate","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"aType","type":"uint8"},{"name":"value","type":"uint256"},{"name":"addr","type":"address"}],"name":"configureModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"providerUID","type":"uint256"}],"name":"joinProvider","outputs":[],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"privateMaxRate","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"rentRate","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"disabledUntil","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"moduleStatus","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"gasProtectMaxRounds","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"providerUID","type":"uint256"},{"name":"roundLimit","type":"uint256"}],"name":"checkReward","outputs":[{"name":"senderReward","type":"uint256"},{"name":"adminReward","type":"uint256"},{"name":"ownerReward","type":"uint256"},{"name":"round","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"privateMinRate","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"clientAddress","type":"address"}],"name":"_isClientPaidUp","outputs":[{"name":"paid","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"newModuleHandlerAddress","type":"address"}],"name":"replaceModuleHandler","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"publicMinRate","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"inputs":[{"name":"forReplace","type":"bool"},{"name":"moduleHandlerAddr","type":"address"},{"name":"dbAddr","type":"address"}],"payable":false,"type":"constructor"},{"anonymous":false,"inputs":[{"indexed":false,"name":"UID","type":"uint256"}],"name":"EProviderOpen","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"UID","type":"uint256"}],"name":"EProviderClose","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"UID","type":"uint256"}],"name":"EProviderNewDetails","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"UID","type":"uint256"},{"indexed":false,"name":"clientAddress","type":"address"}],"name":"EJoinProvider","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"UID","type":"uint256"},{"indexed":false,"name":"clientAddress","type":"address"}],"name":"EPartProvider","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"UID","type":"uint256"},{"indexed":false,"name":"clientAddress","type":"address"},{"indexed":false,"name":"status","type":"bool"}],"name":"EInviteStatus","type":"event"}]
```

### Publisher
Address:
```
0xFBe4273Cafb8Bd5164d034a6A2056Fddd3b2099b
```

ABI:
```javascript
[{"constant":true,"inputs":[{"name":"addr","type":"address"}],"name":"owners","outputs":[{"name":"valid","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"oppositeRate","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"","type":"uint256"}],"name":"announcements","outputs":[{"name":"Type","type":"uint8"},{"name":"start","type":"uint256"},{"name":"end","type":"uint256"},{"name":"open","type":"bool"},{"name":"announcement","type":"string"},{"name":"link","type":"string"},{"name":"oppositable","type":"bool"},{"name":"oppositionWeight","type":"uint256"},{"name":"result","type":"bool"},{"name":"_str","type":"string"},{"name":"_uint","type":"uint256"},{"name":"_addr","type":"address"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"isActive","outputs":[{"name":"success","type":"bool"},{"name":"active","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"minAnnouncementDelay","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"moduleHandlerAddress","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"announcementsLength","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"newModuleAddress","type":"address"}],"name":"replaceModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"id","type":"uint256"}],"name":"closeAnnouncement","outputs":[],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"weight","type":"uint256"},{"name":"oppositable","type":"bool"}],"name":"checkOpposited","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"disconnectModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"from","type":"address"},{"name":"to","type":"address"},{"name":"value","type":"uint256"}],"name":"transferEvent","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"multiOwnerAddress","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"roundID","type":"uint256"},{"name":"reward","type":"uint256"}],"name":"newSchellingRoundEvent","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"Type","type":"uint8"},{"name":"Announcement","type":"string"},{"name":"Link","type":"string"},{"name":"Oppositable","type":"bool"},{"name":"_str","type":"string"},{"name":"_uint","type":"uint256"},{"name":"_addr","type":"address"}],"name":"newAnnouncement","outputs":[],"payable":false,"type":"function"},{"constant":false,"inputs":[],"name":"connectModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"forever","type":"bool"}],"name":"disableModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"","type":"bytes32"},{"name":"","type":"uint256"}],"name":"doDB","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"job","type":"string"},{"name":"data","type":"bytes32"}],"name":"calcDoHash","outputs":[{"name":"hash","type":"bytes32"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"aType","type":"uint8"},{"name":"value","type":"uint256"},{"name":"addr","type":"address"}],"name":"configureModule","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"disabledUntil","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"moduleStatus","outputs":[{"name":"","type":"uint8"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"id","type":"uint256"}],"name":"oppositeAnnouncement","outputs":[],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"ownersForChange","outputs":[{"name":"owners","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"id","type":"uint256"}],"name":"Announcements","outputs":[{"name":"Type","type":"uint8"},{"name":"Start","type":"uint256"},{"name":"End","type":"uint256"},{"name":"Closed","type":"bool"},{"name":"Announcement","type":"string"},{"name":"Link","type":"string"},{"name":"Opposited","type":"bool"},{"name":"_str","type":"string"},{"name":"_uint","type":"uint256"},{"name":"_addr","type":"address"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"id","type":"uint256"}],"name":"invalidateAnnouncement","outputs":[],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"newModuleHandlerAddress","type":"address"}],"name":"replaceModuleHandler","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"},{"name":"","type":"uint256"}],"name":"opponents","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"inputs":[{"name":"moduleHandlerAddr","type":"address"}],"payable":false,"type":"constructor"},{"anonymous":false,"inputs":[{"indexed":false,"name":"id","type":"uint256"},{"indexed":false,"name":"typ","type":"uint8"}],"name":"ENewAnnouncement","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"id","type":"uint256"},{"indexed":false,"name":"addr","type":"address"},{"indexed":false,"name":"value","type":"uint256"}],"name":"EOppositeAnnouncement","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"id","type":"uint256"}],"name":"EInvalidateAnnouncement","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"name":"id","type":"uint256"}],"name":"ECloseAnnouncement","type":"event"}]
```

# Licence

See LICENCE
