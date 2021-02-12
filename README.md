# TestDatasets

Training image pairs for parameter learning.

## Installation 

```julia
pkg> add TestDatasets
```

## Use

```julia
using TestDatasets
dataset = testdataset("cameraman128_5")
```

## Available Datasets

1. Cameraman 128x128 pixels with 5% gaussian noise "cameraman128_5"
2. Cameraman 256x256 pixels with 5% gaussian noise "cameraman256_5"
3. Cameraman 256x256 pixels with 10% gaussian noise "cameraman256_10"
4. Cameraman 512x512 pixels with 10% gaussian noise "cameraman256_10"
5. Faces 128x128 pixels with 5% gaussian noise "faces_5" - 10 training pairs
6. Faces 128x128 pixels with 10% gaussian noise "faces_10" - 10 training pairs
7. Matches 512x512 pixels with 5% gaussian noise "matches_5" - 10 training pairs
8. Matches 512x512 pixels with 10% gaussian noise "matches_10" - 10 training pairs
9. Playing Cards 256x256 pixels with 5% gaussian noise "playing_cards_5" - 5 training pairs
