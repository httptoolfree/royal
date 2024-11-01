A succesfull response to https://api.royalroad.com/v1/account/info
looks like this
{
  "id": 666,
  "email": "6******6@gmail.com",
  "emailConfirmed": true,
  "username": "666",
  "avatar": "",
  "avatarBorderTier": 5,
  "reputationGemTier": 2,
  "premiumTier": "Premium",
  "hasPassword": false,
  "premiumExpiration": "2029-11-01T11:29:24",
  "age": null
}


To Crack the program simply change account/info inside RoyalRoad.Mobile.Client.dll to https://raw.githubusercontent.com/httptoolfree/royal/refs/heads/main/auth
and nop out the Bearer beneath it.

And when saving module only press the Preserve All MD Tokens. Click anything else and it breaks.

This is a shit crack. But its easy.
