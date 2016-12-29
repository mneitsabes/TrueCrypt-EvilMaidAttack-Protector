# TrueCrypt-EvilMaidAttack-Protector

Legacy code for TrueCrypt 7.1a to prevent the Evil Maid Attack. See https://en.wikipedia.org/wiki/Rootkit#Bootkits.
This patch changes TrueCrypt behavior by monitoring changes in unused spaces on connected hard drives en the bootloader. If a change is detected, the user is notified.
