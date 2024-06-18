# BetterItemExportUpdated
Updated version of Martin's BetterItemExport that uses a different Enum for ``PRODUCTQUALITY``.

Ideally, you would use ``EnumWrapper::GetProductQualities()`` so if the item qualities change between game versions, you would not have any issues.

For now, this works. 
