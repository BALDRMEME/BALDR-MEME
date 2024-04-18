
//FUNDING FTX ALAMEDA WALLET 

const SBF_ADDRESS="9uyDy9VDBw4K7xoSkhmCAm8NAFCwu4pkF6JeHUCtVKcX"

spl-token transfer 5HN5PWiQ5gTn4rQ2LZCxkbUtbyPZxoTw91yMfkuAWpDS 1000000000 $SBF_ADDRESS  --allow-unfunded-recipient  --fund-recipient

spl-token transfer 5HN5PWiQ5gTn4rQ2LZCxkbUtbyPZxoTw91yMfkuAWpDS 4 $SBF_ADDRESS --allow-unfunded-recipient  --fund-recipient 


//FREEZING FTX ALAMEDA WALLET

spl-token freeze  E9ZQF76U7Q2CSnaxPworBeuMXzkLg9vsSLy8WQid2X8s --freeze-authority BALDRi9SodAqaHfLec6fcAHe6xZe9z12ikideVBp5tEA

