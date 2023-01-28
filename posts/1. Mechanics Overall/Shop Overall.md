## Sinopse
The [[Merchant Main Character Overall]] has a HouseShop to sell item to [[AdventurersParty Overall]].

## How it works

The [[Merchant Main Character Overall]] will gather/craft various [[Sellable Items]] those items will be sold to adventures that come uppon the shop.

Every `=this.TimerPartysOnShop` there will be [[AdventurersParty Overall]] passing through the shop (every time they arrive a sound cue of a store bell plays), they will remain for `=this.TimerPartysRemainShop`, during this time the player can come to the shop front to sell his [[Sellable Items]].

When the player comes to the shop front with a [[AdventurersParty Overall]] present, the player will evaluate the [[Party Needs]] and choose what items to sell on the [[SellingInstance]]. The items prices will be determined automatically by [[Items Pricing]]. The player wants to sell the most profitable item according to the [[Party Needs]].

### Local Variables
TimerPartysOnShop:: 5 minutes
TimerPartysRemainShop:: 2 minutes