# BetterItemExportUpdated
Updated version of Martin's [BetterItemExport Plugin](https://github.com/Martinii89/BetterItemExport). that uses a different Enum for ``PRODUCTQUALITY``.

This does not use the current item quality name found in RL. This uses the old one for our use-case.

Ideally, you would use ``EnumWrapper::GetProductQualities()`` so if the item qualities change between game versions, you would not have any issues.

For now, this works. 
