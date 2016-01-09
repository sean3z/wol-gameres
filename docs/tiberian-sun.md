# Tiberian Sun
Below are a list of fields available in the Tiberian Sun 2.03 Game Resolution Packet

## Client Information
##### `VERS` Version
This is essentially used to determine whether the game client has the most recent patch
* `type` string
* `example` v2.03

##### `VIDM` Video Memory
Client's available video memory
* `type` int
* `example` 16777216

##### `MEMO` Memory
Client's available RAM
* `type` int
* `example` 1073741823

##### `PROC` Processor
Client's processor type
* `type` integer
* `example` 6

##### `AFPS` Average FPS
Client's Average Frames per Second during the match
* `type` integer
* `example` 56

##### `PNGR` Pings Received
Once a match begins, the server pings each client to keep the WOL connection alive. This is used to determine which player disconnected
* `type` integer
* `example` 1

##### `PNGS` Pings Sent
Similar to the above, this is used to determine how many times the player's connection was able to respond to each ping.
* `type` integer
* `example` 1

##### `FINI` Finish
Whether the client saw the finish of the match.
* `type` bool
* `example` 1
 
##### `OOSY` Out of Sync
Whether the match was considered Out of Sync
* `type` bool
* `example` 1

##### `GSKU` Game SKU
Game SKU
* `type` integer
* `example` 4708

## Match Information
##### `DATE`
Match date
* `type` datetime
* `example` 1452101198

##### `SPED`
Match speed setting
* `type` integer
* `example` 10

##### `TIME`
Timestamp of when the match started
* `type` datetime
* `example` 1452101198

##### `PLRS`
Players in game
* `type` integer
* `example` 4708

##### `WDTT`
Whether game was for World Domination Tour
* `type` bool
* `example` 1

##### `SCEN`
Selected Map
* `type` string
* `example` Terrace

##### `FLAG`
Capture the flag
* `type` bool
* `example` 1

##### `SHAD`
Fog of War
* `type` bool
* `example` 0

##### `AIPL`
Number of AI Players
* `type` integer
* `example` 0

##### `CRAT`
Whether crates are enabled
* `type` bool
* `example` 1

##### `TIBR`
Whether Tiberium is enabled
* `type` bool
* `example` 1

##### `BASE`
Whether bases are enabled
* `type` bool
* `example` 1

##### `CRED`
Match starting credits
* `type` integer
* `example` 10000

##### `DURA`
Match duration (in seconds)
* `type` integer
* `example` 700

##### `TRNY`
Whether match was a tournament game
* `type` bool
* `example` 1

##### `IDNO`
Match Identifier
* `type` integer
* `example` 100


## Player Array
##### `NAM`
Player's name
* `type` integer
* `example` 4708

##### `SID`
Side Index (0 == GDI, 1 == Nod)
* `type` integer
* `example` 4708

##### `TID`
Game SKU
* `type` integer
* `example` 4708

##### `COL`
Game SKU
* `type` integer
* `example` 4708

##### `CRD`
Game SKU
* `type` integer
* `example` 4708

##### `UNL`
Game SKU
* `type` integer
* `example` 4708

##### `INL`
Game SKU
* `type` integer
* `example` 4708

##### `PLL`
Game SKU
* `type` integer
* `example` 4708

##### `BLL`
Game SKU
* `type` integer
* `example` 4708

##### `UNB`
Game SKU
* `type` integer
* `example` 4708

##### `INB`
Game SKU
* `type` integer
* `example` 4708

##### `PLB`
Game SKU
* `type` integer
* `example` 4708

##### `BLB`
Game SKU
* `type` integer
* `example` 4708

##### `UNK`
Game SKU
* `type` integer
* `example` 4708

##### `INK`
Game SKU
* `type` integer
* `example` 4708

##### `PLK`
Game SKU
* `type` integer
* `example` 4708

##### `BLK` 
Game SKU
* `type` integer
* `example` 4708

##### `BLC`
Game SKU
* `type` integer
* `example` 4708

##### `CRA`
Game SKU
* `type` integer
* `example` 4708

##### `HRV`
Game SKU
* `type` integer
* `example` 4708

##### `CMP`
Game SKU
* `type` integer
* `example` 4708

##### `IPA`
Game SKU
* `type` integer
* `example` 4708

##### `CID`
Game SKU
* `type` integer
* `example` 4708

##### `LCN`
Game SKU
* `type` integer
* `example` 4708

#### Unknown
##### `SPID`
