# RelyingParty

The **RelyingParty** (used as `XSTSRelyingParty` in this library) is a trusted domain configured by Microsoft and / or its partners to create a XSTS token which is intended to be used for a targeted service. For instance, if you use `rp://playfabapi.com/` you will be able to interact with the official Playfab.com API. A partial list can be found here: https://title.mgt.xboxlive.com/titles/default/endpoints?type=1.

Please note that each service may have its own parties such as **Minecraft** `rp://api.minecraftservices.com/`, **Sea Of Thieves** `http://athena.prod.msrareservices.com/` or **Gears 5** `http://xsts.gearsofwar.net/`.